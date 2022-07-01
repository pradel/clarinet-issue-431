# clarinet-issue-431

Repo reproducing clarinet issue 431.

The contract is the same as the one deployed by arkadiko https://explorer.stacks.co/txid/SP2C2YFP12AJZB4MABJBAJ55XECVS7E4PMMZ89YZR.arkadiko-multi-hop-swap-v1-1?chain=mainnet.

Steps to reproduce:

1. Clone the repo
2. Run `clarinet check` at the root of the repo
3. See the `thread 'main' panicked at 'unable to retrieve contract', src/frontend/cli.rs:1438:18` error
