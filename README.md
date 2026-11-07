# hushmark-demo

A demo repository for the [Hushmark](https://github.com/Ritapossible/Hushmark) GitHub App.

Hushmark is installed here as a GitHub App (not the Action) and runs in `block` mode
(`.hushmark.yml`). Its pull requests show:

- a hidden instruction aimed at AI agents, failing the `Hushmark` check with a verified finding
  and a receipt anchored on NEAR testnet;
- a maintainer re-running the review by commenting `/hushmark`;
- a bot commenting `/hushmark` and being refused (`not_maintainer`): nothing is posted.

The files in pull requests here are deliberately suspicious. Do not merge them.
