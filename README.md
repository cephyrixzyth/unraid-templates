# Oneirodex for Unraid Community Applications

This repository contains the Unraid Community Applications profile and the Docker template for [Oneirodex](https://github.com/cephyrixzyth/Oneirodex), a self-hosted household game library.

## Install

Install **Oneirodex** from the Unraid Apps tab. The template runs a single container with PostgreSQL embedded; no separate database container is needed.

- Keep **Appdata** on cache or SSD storage. It contains the database, generated secrets, logs, and user data. Back it up with the container stopped.
- Map **Games** to the share to scan. The template mounts this path read-only at `/storage`.
- Open the WebUI after installation and complete the first-run setup wizard.

The image is published at [Docker Hub](https://hub.docker.com/r/cephyrixzyth/oneirodex) for `linux/amd64` and `linux/arm64`.

## Links

- Project and source: [cephyrixzyth/Oneirodex](https://github.com/cephyrixzyth/Oneirodex)
- Unraid setup guide: [Community Apps and Docker Hub](https://github.com/cephyrixzyth/Oneirodex/blob/main/docs/runbooks/unraid-community-apps.md)
- Issues: [Oneirodex issue tracker](https://github.com/cephyrixzyth/Oneirodex/issues)

Oneirodex is intended for software you are authorized to share. The image does not include BIOS or firmware.
