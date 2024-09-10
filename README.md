# Lima: Linux Machines

Lima launches Linux virtual machines with automatic file sharing and port forwarding (similar to WSL2).

✅ Automatic file sharing

✅ Automatic port forwarding

✅ Built-in support for containerd (Other container engines can be used too)

✅ Intel on Intel

✅ ARM on Intel

✅ ARM on ARM

✅ Intel on ARM

✅ Various guest Linux distributions: AlmaLinux, Alpine, Arch Linux, Debian, Fedora, openSUSE, Oracle Linux, Rocky, Ubuntu (default), …

Related project: sshocker (ssh with file sharing and port forwarding)

This project is unrelated to The Lima driver project (driver for ARM Mali GPUs).

> This repository is for personal lima configuration files and provisioning scripts

## Basic command for creating virtual machine instance on Lima

```sh
$ limactl create --name=<instance> <config(path|url)>
```

>Default configuration file reference
> https://github.com/lima-vm/lima/blob/master/examples/default.yaml


> Lima Github Repository
> https://github.com/lima-vm/lima

> Lima Official Documentation
> https://lima-vm.io/docs/

