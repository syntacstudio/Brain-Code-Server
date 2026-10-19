# Brain Code Server

Packages of Brain Code Server, the remote end of Brain Code's remote windows (Remote - SSH): a
remote machine downloads the package for its architecture the first time a window connects to it,
as VS Code Server is downloaded for VS Code.

Each release `braincode-server-<version>` holds:

- `braincode-server-linux-x64.tar.gz`
- `braincode-server-linux-arm64.tar.gz`

A package is one folder with the server, its launcher (`bin/braincode-server`) and the Node.js it
runs on.
