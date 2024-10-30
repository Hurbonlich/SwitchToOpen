# Virtualisation

## Hyperviseurs de type 1 (Bare-metal)
  - [Proxmox VE](https://www.proxmox.com/en/proxmox-ve) : Solution de virtualisation open source avec support des conteneurs et des machines virtuelles KVM
  - [XCP-ng](https://xcp-ng.org/) : Hyperviseur open source basé sur XenServer, avec gestion complète des machines virtuelles et du réseau
  - [KVM (Kernel-based Virtual Machine)](https://www.linux-kvm.org/) : Technologie de virtualisation native sous Linux, permettant d'exécuter des systèmes d'exploitation invités sur des serveurs
  - [Xen Project](https://xenproject.org/) : Hyperviseur open source permettant d'exécuter plusieurs systèmes d'exploitation invités sur des serveurs physiques
  - [oVirt](https://www.ovirt.org/) : Plateforme de gestion de la virtualisation basée sur KVM, utilisée pour la gestion des datacenters

## Hyperviseurs de type 2 (Virtualisation hébergée)
  - [VirtualBox (édition open source)](https://www.virtualbox.org/) : Hyperviseur open source permettant de créer et exécuter des machines virtuelles sur des systèmes d'exploitation hôtes
  - [GNOME Boxes](https://wiki.gnome.org/Apps/Boxes) : Interface simple pour la gestion des machines virtuelles, utilisant libvirt et KVM sous Linux
  - [QEMU](https://www.qemu.org/) : Émulateur open source permettant de virtualiser des systèmes d'exploitation ou d'émuler différentes architectures matérielles
  - [VMware Player (version gratuite)](https://www.vmware.com/products/workstation-player.html) : Version gratuite de VMware pour exécuter des machines virtuelles

## Virtualisation de conteneurs
  - [Docker](https://www.docker.com/) : Plateforme open source de conteneurisation permettant d'exécuter des applications dans des environnements isolés
  - [LXC (Linux Containers)](https://linuxcontainers.org/) : Système de conteneurisation open source permettant d'exécuter plusieurs systèmes Linux isolés sur un seul hôte
  - [Podman](https://podman.io/) : Alternative à Docker pour la gestion des conteneurs sans démon, offrant des fonctionnalités similaires
  - [Kubernetes](https://kubernetes.io/) : Plateforme open source pour l'orchestration des conteneurs, utilisée pour la gestion des applications conteneurisées à grande échelle
  - [rkt (Rocket)](https://coreos.com/rkt/) : Outil de conteneurisation open source, conçu pour des environnements plus sécurisés que Docker

## Virtualisation légère pour environnements spécifiques
  - [Multipass](https://multipass.run/) : Solution open source pour exécuter des machines virtuelles légères sous Linux, Windows et macOS, avec intégration Ubuntu
  - [Vagrant](https://www.vagrantup.com/) : Outil open source pour automatiser la création et la gestion des environnements de développement virtuels
  - [Firecracker](https://firecracker-microvm.github.io/) : MicroVMs open source légères pour des déploiements rapides de conteneurs et de fonctions serverless
  - [bhyve](https://bhyve.org/) : Hyperviseur léger natif sous FreeBSD, utilisé pour la virtualisation rapide et efficace

## Outils de virtualisation réseau
  - [Open vSwitch](https://www.openvswitch.org/) : Commutateur virtuel open source conçu pour automatiser les réseaux dans des environnements virtualisés
  - [Flannel](https://github.com/flannel-io/flannel) : Réseau open source pour les conteneurs Kubernetes, permettant de configurer un réseau overlay simple
  - [Calico](https://www.projectcalico.org/) : Solution de mise en réseau open source pour les environnements cloud et conteneurisés
  - [Cilium](https://cilium.io/) : Solution open source pour la connectivité et la sécurité des réseaux de conteneurs

