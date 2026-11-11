# awesome-block-builders
A list of ethereum Block Builders and their RPC endpoints in no particular order.

For a complete list of every block builder that lands blocks on-chain see [mev-builder](https://etherscan.io/accounts/label/mev-builder) label on Etherscan.

| Name | RPC | Notes |
|---|---|---|
| beaverbuild | https://rpc.beaverbuild.org/ |  |
| builder0x69 | https://builder0x69.io | |
| Flashbots | https://relay.flashbots.net | |
| bloXroute | https://mev.api.blxrbdn.com | bloXroute account required |
| Eden Network | https://api.edennetwork.io/v1/bundle | |
| eth-builder | https://eth-builder.com | |
| lightspeedbuilder | https://rpc.lightspeedbuilder.info/ | |
| Manifold Finance | https://api.securerpc.com/v1 | |
| buildAI | https://BuildAI.net | |
| payload | https://rpc.payload.de | |
| rsync-builder | https://rsync-builder.xyz/ | |
| nfactorial | https://rpc.nfactorial.xyz/ | |
| lokibuilder | https://rpc.lokibuilder.xyz/ | |
| Aqua Builder | https://rpc.aquabuilder.online | Free, no account. `refundPercent`/`refundRecipient` required (91% refunds, capped at 91% of builder profit). Flashbots-compatible: `eth_sendBundle`, `eth_callBundle`, `eth_cancelBundle`, `mev_sendBundle`. extra_data `Aqua Builder`. [Docs](https://aquabuilder.online/docs/) |

# Dashboards
- [Builder profitability](https://www.relayscan.io/builder-profit?t=24h)

# Open-source code
- [Flashbots builder](https://github.com/flashbots/builder)
- [mev-rs](https://github.com/ralexstokes/mev-rs)
