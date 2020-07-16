# self-hosted
![](https://img.shields.io/website?down_color=red&up_color=green&url=https%3A%2F%2Fwhoami.estysdesu.com)

self-hosted is a my personal maintained infrastructure as files of my self-hosted server.

## TODO Major
- [ ] Deployment: 
  1. [ ] Kubernetes: [Minikube](https://kubernetes.io/docs/tasks/configure-pod-container/translate-compose-kubernetes/) and [Helm](https://helm.sh/)
  1. [ ] Nix: [NixOps](https://nixos.org/nixops/manual/)
- [ ] OS: 
  1. [Fedora Server 32](https://getfedora.org/en/server/download/)
  1. [NixOS](https://nixos.wiki/wiki/Install_NixOS_on_Hetzner_Online) (Hetzner Cloud (VM) not Online (bare metal))
- [ ] FS: btrfs


## TODO Services
- [ ] Dash: [Traefik dash](https://docs.traefik.io/operations/dashboard/) [rule](https://docs.traefik.io/v2.2/operations/dashboard/#dashboard-router-rule)
- [ ] RSS reader: [Miniflux](https://github.com/miniflux/miniflux)
- [ ] Cloud: [Nextcloud](https://blog.ssdnodes.com/blog/self-hosting-nextcloud/#Why_is_selfhosting_Nextcloud_a_good_idea_13)
- [ ] Password store: [Bitwarden](https://selfhostedhome.com/self-host-password-management-bitwarden/) (bitwarden_rs)
- [ ] Tracking: [Kanboard](https://github.com/kanboard/kanboard)

## TODO Updates
- [ ] Build custom vscode container for [settings sync](https://github.com/cdr/code-server/issues/148)
- [ ] Change [`working_dir`](https://docs.docker.com/compose/compose-file/#domainname-hostname-ipc-mac_address-privileged-read_only-shm_size-stdin_open-tty-user-working_dir) for vscode to `/home/coder/project`
- [ ] Add settings to Jupyter docker image
