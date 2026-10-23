# ReserveRoute — cli

Open-source planning for Stellar sponsored-reserve transfers and removals. The first adapter supports credit trustlines, with explicit blockers and unsigned transaction preparation.

Install the backend with npm ci first. Run node cli.mjs sample, node cli.mjs plan input.json, node cli.mjs capture G... G..., or node cli.mjs build input.json. build performs a live testnet refresh and prints unsigned XDR only. Run npm test and npm run demo.

Read [INTEGRATION.md](INTEGRATION.md) for the connected setup, trust boundaries and supported scope. Components: [engine](https://github.com/reserveroute/reserveroute-engine), [backend](https://github.com/reserveroute/reserveroute-backend), [frontend](https://github.com/reserveroute/reserveroute-frontend), [cli](https://github.com/reserveroute/reserveroute-cli), [fixtures](https://github.com/reserveroute/reserveroute-fixtures).

MIT licensed. Local testnet MVP, not a complete sponsorship inventory or production signing service.
