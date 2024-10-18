# Virtualisation

## Hyperviseurs de type 1 (Bare-metal)
- **Propriétaires** : VMware ESXi, Microsoft Hyper-V
- **Open Source** :
  - [Proxmox VE](https://www.proxmox.com/en/proxmox-ve) (Solution de virtualisation open source avec support des conteneurs et des machines virtuelles KVM)
  - [XCP-ng](https://xcp-ng.org/) (Hyperviseur open source basé sur XenServer, avec gestion complète des machines virtuelles et du réseau)
  - [KVM (Kernel-based Virtual Machine)](https://www.linux-kvm.org/) (Technologie de virtualisation native sous Linux, permettant d'exécuter des systèmes d'exploitation invités sur des serveurs)
  - [Xen Project](https://xenproject.org/) (Hyperviseur open source permettant d'exécuter plusieurs systèmes d'exploitation invités sur des serveurs physiques)
  - [oVirt](https://www.ovirt.org/) (Plateforme de gestion de la virtualisation basée sur KVM, utilisée pour la gestion des datacenters)

## Hyperviseurs de type 2 (Virtualisation hébergée)
- **Propriétaires** : VMware Workstation, Oracle VirtualBox (version commerciale)
- **Open Source** :
  - [VirtualBox (édition open source)](https://www.virtualbox.org/) (Hyperviseur open source permettant de créer et exécuter des machines virtuelles sur des systèmes d'exploitation hôtes)
  - [GNOME Boxes](https://wiki.gnome.org/Apps/Boxes) (Interface simple pour la gestion des machines virtuelles, utilisant libvirt et KVM sous Linux)
  - [QEMU](https://www.qemu.org/) (Émulateur open source permettant de virtualiser des systèmes d'exploitation ou d'émuler différentes architectures matérielles)
  - [VMware Player (version gratuite)](https://www.vmware.com/products/workstation-player.html) (Version gratuite de VMware pour exécuter des machines virtuelles)

## Plateformes de gestion de la virtualisation
- **Propriétaires** : VMware vCenter, Citrix XenCenter
- **Open Source** :
  - [Proxmox VE](https://www.proxmox.com/en/proxmox-ve) (Plateforme de gestion de la virtualisation avec support intégré pour les conteneurs LXC et les machines virtuelles KVM)
  - [oVirt](https://www.ovirt.org/) (Plateforme de gestion de la virtualisation basée sur KVM et libvirt, conçue pour les infrastructures à grande échelle)
  - [OpenStack](https://www.openstack.org/) (Suite de logiciels open source pour la gestion des infrastructures cloud et des environnements virtualisés)
  - [Xen Orchestra](https://xen-orchestra.com/) (Outil open source pour la gestion des environnements XenServer et XCP-ng)
  - [Kimchi](https://github.com/kimchi-project/kimchi) (Interface web open source pour gérer les machines virtuelles basées sur KVM)

## Virtualisation de conteneurs
- **Propriétaires** : Docker Enterprise, Red Hat OpenShift
- **Open Source** :
  - [Docker](https://www.docker.com/) (Plateforme open source de conteneurisation permettant d'exécuter des applications dans des environnements isolés)
  - [LXC (Linux Containers)](https://linuxcontainers.org/) (Système de conteneurisation open source permettant d'exécuter plusieurs systèmes Linux isolés sur un seul hôte)
  - [Podman](https://podman.io/) (Alternative à Docker pour la gestion des conteneurs sans démon, offrant des fonctionnalités similaires)
  - [Kubernetes](https://kubernetes.io/) (Plateforme open source pour l'orchestration des conteneurs, utilisée pour la gestion des applications conteneurisées à grande échelle)
  - [rkt (Rocket)](https://coreos.com/rkt/) (Outil de conteneurisation open source, conçu pour des environnements plus sécurisés que Docker)

## Solutions de virtualisation pour postes de travail
- **Propriétaires** : Citrix Virtual Apps and Desktops, VMware Horizon
- **Open Source** :
  - [QEMU](https://www.qemu.org/) (Outil d'émulation et de virtualisation pour exécuter différents systèmes d'exploitation sur des postes de travail)
  - [SPICE](https://www.spice-space.org/) (Protocole open source pour virtualiser des environnements de bureau et améliorer l'expérience utilisateur à distance)
  - [X2Go](https://wiki.x2go.org/doku.php) (Solution open source pour la virtualisation et l'accès à distance des environnements de bureau Linux)
  - [FreeRDP](https://www.freerdp.com/) (Client open source pour le protocole Remote Desktop Protocol (RDP), utilisé pour la virtualisation de postes de travail)

## Virtualisation légère pour environnements spécifiques
- **Propriétaires** : Parallels Desktop, VMware Fusion
- **Open Source** :
  - [Multipass](https://multipass.run/) (Solution open source pour exécuter des machines virtuelles légères sous Linux, Windows et macOS, avec intégration Ubuntu)
  - [Vagrant](https://www.vagrantup.com/) (Outil open source pour automatiser la création et la gestion des environnements de développement virtuels)
  - [Firecracker](https://firecracker-microvm.github.io/) (MicroVMs open source légères pour des déploiements rapides de conteneurs et de fonctions serverless)
  - [bhyve](https://bhyve.org/) (Hyperviseur léger natif sous FreeBSD, utilisé pour la virtualisation rapide et efficace)

## Outils de virtualisation réseau
- **Propriétaires** : VMware NSX, Cisco ACI
- **Open Source** :
  - [Open vSwitch](https://www.openvswitch.org/) (Commutateur virtuel open source conçu pour automatiser les réseaux dans des environnements virtualisés)
  - [Flannel](https://github.com/flannel-io/flannel) (Réseau open source pour les conteneurs Kubernetes, permettant de configurer un réseau overlay simple)
  - [Calico](https://www.projectcalico.org/) (Solution de mise en réseau open source pour les environnements cloud et conteneurisés)
  - [Cilium](https://cilium.io/) (Solution open source pour la connectivité et la sécurité des réseaux de conteneurs)

