# `pkgbuilder` docker image

[![](https://images.microbadger.com/badges/image/bpfk/pkgbuilder.svg)](https://microbadger.com/images/bpfk/pkgbuilder)
[![](https://images.microbadger.com/badges/version/bpfk/pkgbuilder.svg)](https://microbadger.com/images/bpfk/pkgbuilder)

Since D support is not part of Alpine Linux,
it is currently impossible to compile D code without going through some hoops.
BPF Korea has been building packages that allow to build D programs on Alpine.

This repository is the base image used to build those packages.
It includes a user, as `abuild` refuses to build as `root`,
`alpine-sdk`, and a preinstalled default key.
