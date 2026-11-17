# Stageproof

Stageproof checks a Helm chart upgrade before you merge it.

The command line tool compares the chart you run with the chart a pull request wants, and exits 0, 1, or 2. It does not upgrade a Kubernetes cluster, and it does not change a cluster you already have.

- Code and releases: [stageproof/stageproof](https://github.com/stageproof/stageproof)
- Documentation: [stageproof.github.io/stageproof](https://stageproof.github.io/stageproof/)
- Install: `brew install stageproof/stageproof/stageproof`
