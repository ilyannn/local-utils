# local-utils

Utilities from my `~/.local` folder on Linux:

- [prettier](bin/prettier): using Prettier in a container with non-root user, with rootless podman
- [git-prettier](bin/git-prettier): prettifying files in the git repo, but only if it's clean

### Notes on rootless Podman

- [Podman issue](https://github.com/containers/podman/issues/3990)
- [Article on rootless Podman](https://www.redhat.com/sysadmin/rootless-podman-makes-sense)
- [Syntax of `--uidmap`](https://stackoverflow.com/a/70774211)
