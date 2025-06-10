## GitHub Copilot Chat

- Extension Version: 0.27.3 (prod)
- VS Code: vscode/1.100.3
- OS: Windows

## Network

User Settings:
```json
  "github.copilot.advanced.debug.useElectronFetcher": true,
  "github.copilot.advanced.debug.useNodeFetcher": false,
  "github.copilot.advanced.debug.useNodeFetchFetcher": true
```

Connecting to https://api.github.com:
- DNS ipv4 Lookup: 20.201.28.148 (41 ms)
- DNS ipv6 Lookup: Error (75 ms): getaddrinfo ENOTFOUND api.github.com
- Proxy URL: None (2 ms)
- Electron fetch (configured): HTTP 200 (199 ms)
- Node.js https: HTTP 200 (180 ms)
- Node.js fetch: HTTP 200 (298 ms)
- Helix fetch: HTTP 200 (207 ms)

Connecting to https://api.individual.githubcopilot.com/_ping:
- DNS ipv4 Lookup: 140.82.114.22 (17 ms)
- DNS ipv6 Lookup: Error (34 ms): getaddrinfo ENOTFOUND api.individual.githubcopilot.com
- Proxy URL: None (3 ms)
- Electron fetch (configured): HTTP 200 (530 ms)
- Node.js https: HTTP 200 (513 ms)
- Node.js fetch: HTTP 200 (516 ms)
- Helix fetch: HTTP 200 (498 ms)

## Documentation

In corporate networks: [Troubleshooting firewall settings for GitHub Copilot](https://docs.github.com/en/copilot/troubleshooting-github-copilot/troubleshooting-firewall-settings-for-github-copilot).