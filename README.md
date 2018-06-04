## Rivine product organization

This repository is the starting point for people to find their way in all other repos in the Rivine product organization.

- owners of this organization:
  - [Rob Van Mieghem](http://github.com/robvanmieghem)
  - [Glen De Cauwsemaecker](http://github.com/glendc)

Upcoming milestones:
- [1.0.7 kanban](https://waffle.io/rivine/home?milestone=1.0.7%20wallet%20improvements) Feature release (Planned Release date: 20/06/2018)
  - [Improved quality of Rivine codebase](https://docs.greenitglobe.com/gig/org_development/issues/76)
  - [Rivine Wallet Improvements](https://docs.greenitglobe.com/gig/org_development/issues/74)
  - [Ethereum Atomic Swap Support](https://docs.greenitglobe.com/gig/org_development/issues/75)

Previous milestones:
- 1.0.6: Feature release (Release date: 04/06/2018)
  - fix bugs introduced to atomic swap CLI commands in 1.0.5
  - improve UX of atomic swap CLI commands and align the API to the decred/atomicswap tools
  - introduce multisig in the form of a new condition and fulfillment
- 1.0.5: Feature release (Release date: 09/05/2018)
  - breaking release: new transaction version, deprecating the original transaction version as legacy;
  - breaking release: coin/blockstake output models have changed;
  - support time locked tokens;
  - improved explorer graphs;
- 1.0.4: Feature release (Release date: 03/05/2018)
  - add graphs to threefold explorer web UI;
  - investigate and resolve zero-os crashes;
- 1.0.3: Bugfix release (Release date: 19/04/2018)
  - hard reset of standard (tfchain) net;
  - add feature to allow a wallet to be recovered from a seed/mnemonic;
- 1.0.2: Bugfix release (Release date: 09/04/2018)
  - p2p-network communication fixes;
- 1.0.0: Bugfix release (Release date: 31/03/2018)
  - bugfix anything that needs bugfixing, prior to the tf launch;
  - improve what needs improving, prior to the tf launch;
  - includes also a 1.0.1 release, which is the actual working version, replacing 1.0.0 right after launch;
- 0.5.0: Feature release (Released together with 0.6.0)
  - registration of data: transfer data and replicate data on a KV storage;
  - allow for different nets of the same type of blockchain;
  - allow for better configuration of blockchain implementations;
- 0.6.0: Feature release (Release date: 29/03/2018)
  - implement new transaction structure;
  - support atomic swaps;

Code Repos:
- [rivine](https://github.com/rivine/rivine): the core blockchain technology
- [UI](https://github.com/rivine/rivine-UI): a web GUI for rivine
- [explorer](https://github.com/rivine/explorer): a simple web explorer GUI for rivine

Related Code Repos:
- [tfchain](https://github.com/threefoldfoundation/tfchain): the threefold blockchain code repo (using Rivine)
