# LevelTen Energy

LevelTen Energy operates a two-sided digital marketplace and transaction platform for carbon-free
energy. Clean energy buyers, advisors, project developers, utilities and financiers use the LevelTen
Energy Marketplace to compare power purchase agreement (PPA) offers, run NPV and settlement cashflow
analysis, evaluate risk scenarios, and track projects across North America and Europe. The company also
publishes market intelligence products including MarketPulse, the LevelTen PPA Price Index, and Market
Transparency Reports.

Backed by: techstars — https://leveltenenergy.com/

## API surface

LevelTen Energy runs an authenticated API at `https://api.levelten.energy`, which self-identifies as
"the API for LevelTen Energy" and directs callers to log in at the marketplace. As of the 2026-07-19
enrichment pass there is **no public developer portal, API reference, OpenAPI/GraphQL/AsyncAPI
specification, SDK, package, CLI, MCP server, changelog, status page, or `/.well-known/` discovery
document**. Enrichment is therefore limited to identity, link properties, and live security probes.

## Artifacts

- `security/levelten-energy-domain-security.yml` — TLS/HSTS/DNSSEC/CAA/SPF/DMARC probe
- `well-known/levelten-energy-well-known.yml` — recorded `/.well-known/` and spec-discovery probe (0 found)
- `llms/levelten-energy-llms.txt` — generated llms.txt
