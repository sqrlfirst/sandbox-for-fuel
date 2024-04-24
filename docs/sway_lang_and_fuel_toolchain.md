

## Sway 

Sway is a DSL based on Rust.

Download and install the latest version of Sway
```cliy
curl --proto '=https' --tlsv1.2 -sSf \
https://install.fuel.network/fuelup-init.sh | sh
```

Install and set beta-4 to be default toolchain
```cli
fuelup toolchain install bets-4
fuelup default beta-4
```

What was installed

- `forc` - the fuel orchestrator which is the equavalent of Rust `cargo` tool.
- `forc-lsp` - the language server for Sway to provide autocomplete and intellisense in your code editor.
- `forc-fmt` - the code formater for Sway.
- `fuel-core` - implementation of the Fuel protocol - used to run a local Fuel node during tests.

