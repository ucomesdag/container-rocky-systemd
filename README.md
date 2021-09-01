Rocky Linux Systemd Container Image
=====================

This Containerfile can build containers capable to use systemd.

[![rocky build status](https://quay.io/repository/ucomesdag/rocky/status "Container Repository on Quay")](https://quay.io/repository/ucomesdag/rocky)

Branches
--------

This repository has multiple branches that relate to CentOS versions.

|Branch |Rocky Linux Version |Container image tag|
|-------|--------------------|-------------------|
|main   |latest (8)          |latest             |

Pull strategy
-------------

The different branches are **not** merged, they live as individual branches.

Manually starting
-----------------

```
podman run \
  --tty \
  --privileged \
  --volume /sys/fs/cgroup:/sys/fs/cgroup:ro \
  quay.io/ucomesdag/rocky
```
