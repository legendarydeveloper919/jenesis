## Compile contracts

Compile your contracts by running the following command inside your
project directory:

```
jenesis compile
```
This will compile all packages in your project's contracts directory and output the wasm code under the artifacts directory. If using a cargo workspace, jenesis will automatically detect this and the compiled contracts will appear in the `contracts/artifacts/`. Otherwise, they will go to the `artifacts` directory under the individual contracts.

> *Note: ```jenesis compile``` requires that docker is running and configured with permissions for your user.*