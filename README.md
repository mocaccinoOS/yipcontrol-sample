# yipcontrol-sample

This repository is a sample for a `yipcontrol` repository.

`/etc/yip.d` is assumed to be a git repository in the host system and its configured properly to `git pull` (if you use a private repo, be sure to set your remote accordingly), so `yip` can automatically pull updates.

`yip` doesn't enforce any directory layout, and this repository can be also run locally or in a container with `yip -s reconcile <folder>`.
 
In Mocaccino Micro, this sample can be used with the runit-service to automatically control machines remotely [ see also here](https://www.mocaccino.org/docs/micro/service-management/#yip-integration).