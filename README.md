# valkey-static

This docker image contains/the release files are a statically linked build of valkey without TLS. <br>
It can be seen as a drop-in replacement for the official redis image.

Use: ``ghcr.io/donno/valkey-static`.
It includes valkey-sever and valkey-cli (with links to the old redis names, all in `/usr/local/bin`). <br>
**Note: the protected mode is disabled by default for the docker image and the binaries.** You can enable it by adding `--protected-mode yes`
