## ASA Stats terminal app

See [dev](https://github.com/dragmz/goas-release/releases/tag/dev) release for the latest, bleeding edge binaries.

## Source code

Not available yet.

### Supported OS

Windows, Linux, macOS (see https://go.dev/dl/ for a minimum OS version required).

### How to use

1. Download a binary release for your OS
2. Run it providing at least one of the following args:

    `-demo`, e.g. `./goas_linux_amd64 -demo`
    
    or
    
    `-token` and `-input`, e.g. `goas_windows_amd64 -token ASA_STATS_API_TOKEN -input 2EVGZ4BGOSL3J64UYDE2BUGTNTBZZZLI54VUQQNZZLYCDODLY33UGXNSIU,VW55KZ3NF4GDOWI7IPWLGZDFWNXWKSRD5PETRLDABZVU5XPKRJJRK3CBSU` <- the two are demo accounts BTW

### Arguments

- `-demo` - run the tool in a demo mode, with a hardcoded snapshot of some demo accounts
- `-token` - ASA Stats API token (available to DAO members only at the time of writing; see [ASA Stats Discord](https://discord.gg/Vjx7w7pAC7) for details on how to get one)
- `-input` - comma separated list of Algorand addresses (or names)
- `-path` - base configs path (`[current working dir]/.goas` by default)

### Configs

- `.goas/token` - (optionally) put your ASA Stats API token in the file so the `-token` arg is no longer needed
