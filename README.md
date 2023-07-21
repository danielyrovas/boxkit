# boxkit

A dev kit for use with distrobox/toolbox or podman/docker. Contains most [modern unix](https://github.com/ibraheemdev/modern-unix)
tools, with chezmoi for config management.

It uses the latest Alpine toolbox image from [Toolbx Community images](https://github.com/toolbx-images/images).

### Create Box

```
distrobox create -i ghcr.io/danielyrovas/boxkit -n boxkit
distrobox enter boxkit
```

## Finding Good Base Images

These are a set of mostly stock images with packages needed to run as a toolbox/distrobox already installed.
