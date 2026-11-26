# BlackVault Commander MCP

Official client integration documentation for the hosted BlackVault Commander service by Liquidity Labs Studio. This repository contains public configuration examples and usage guidance, not proprietary server source code.

## Connect
1. Sign up at https://commander.liquiditylabsstudio.com/ and enroll a computer you own or are authorized to manage.
2. In a client supporting remote Streamable HTTP MCP and OAuth, add https://commander.liquiditylabsstudio.com/mcp.
3. Complete OAuth and grant only the access you need. Approve operations locally where required.
4. Start with 'List my authorized devices' or 'Check device status'.

## Kiro and LM Studio

[![Add to Kiro](https://kiro.dev/images/add-to-kiro.svg)](https://kiro.dev/launch/mcp/add?name=blackvault-commander&config=%7B%22url%22%3A%22https%3A%2F%2Fcommander.liquiditylabsstudio.com%2Fmcp%22%2C%22disabled%22%3Afalse%2C%22autoApprove%22%3A%5B%5D%7D)
Use the remote configuration example in kiro-mcp.json for Kiro. LM Studio users can use the official one-click installer link below, or add the example in lmstudio-mcp.json.

[Add to LM Studio](https://lmstudio.ai/install-mcp?config=eyJ1cmwiOiJodHRwczovL2NvbW1hbmRlci5saXF1aWRpdHlsYWJzc3R1ZGlvLmNvbS9tY3AifQ%3D%3D&name=blackvault-commander)

## Security and support
Device discovery and diagnostics are scoped to the authenticated account. Further operations require the relevant scopes and device-local approval where applicable. Client support determines tool availability. No credentials are included in the examples.

Public MCP Registry ID: io.github.theliquidationlab/blackvault-commander

- Website: https://commander.liquiditylabsstudio.com/
- Support: https://commander.liquiditylabsstudio.com/support
- Privacy: https://commander.liquiditylabsstudio.com/privacy
- Terms: https://commander.liquiditylabsstudio.com/terms

Publisher: Liquidity Labs Studio. Contact: blackvault@liquiditylabsstudio.com.
