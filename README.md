# self-hosted
![](https://img.shields.io/website?down_color=red&up_color=green&url=https%3A%2F%2Fwhoami.estysdesu.com)

self-hosted is a my personal maintained infrastructure as files of my self-hosted server.

## TODO Infrastructure
- [ ] Deployment: 
  1. Kubernetes: [Minikube](https://kubernetes.io/docs/tasks/configure-pod-container/translate-compose-kubernetes/) and [Helm](https://helm.sh/)
  1. Nix: [NixOps](https://nixos.org/nixops/manual/)
- [ ] OS: 
  1. [Fedora Server 32](https://getfedora.org/en/server/download/)
  1. [NixOS](https://nixos.wiki/wiki/Install_NixOS_on_Hetzner_Online) (Hetzner Cloud (VM) not Online (bare metal))
- [ ] FS: btrfs

## TODO Services
- [ ] **Limit services**: 
  1. root: estysdesu.github.io (migrate to hugo)
  1. cloud: [Nextcloud](https://blog.ssdnodes.com/blog/self-hosting-nextcloud/#Why_is_selfhosting_Nextcloud_a_good_idea_13)
  1. passwd: [Bitwarden](https://selfhostedhome.com/self-host-password-management-bitwarden/) (bitwarden_rs)
  1. rss: [Miniflux](https://github.com/miniflux/miniflux)
  1. todo: [Kanboard](https://github.com/kanboard/kanboard)
  1. dev (if VM powerful enough)
    1. **?** VS Code (OTG editing)
    1. **?** Jupyter (allows UI looking the same without customizing every machine)
  1. monitoring
    1. **?** [cockpit](https://cockpit-project.org/) (if Fedora)
    1. [traefik dash](https://docs.traefik.io/operations/dashboard/)
    1. [homer](https://github.com/bastienwirtz/homer)

## TODO Updates
- [ ] VS Code:	
  1. [Settings sync](https://github.com/cdr/code-server/issues/148)	
  1. [`working_dir`](https://docs.docker.com/compose/compose-file/#domainname-hostname-ipc-mac_address-privileged-read_only-shm_size-stdin_open-tty-user-working_dir) = `/home/coder/project`	
- [ ] Jupyter:
  1. Theming & settings ([my Jupyter docker image](https://github.com/estysdesu/jupyter-stack))
