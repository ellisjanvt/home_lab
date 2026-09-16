# home_lab

## OVerview
I built my homelab to create my own home server and personal cloud, giving me a place to store files, run self-hosted services, and to build my own cyber range.

## Diagram
└── 
                    Internetasd
                       │
                 Home Router 
                       │
                2.5 GbE Switch
                 /           \
                /             \
       Proxmox Server       ZimaBoard2
          │                   │
       VMs / LXCs          NAS Storage
          │                   │
      Cyber Range       Docker Services
                              │
                       Personal Cloud

## Hardware

| HP ProDesk 600 G6 Mini | Virtualization / Proxmox server |
| ZimaBoard 2 | NAS and self-hosted services |
| HDD Storage | Personal cloud and backups |
| 2.5 GbE Network | High-speed local networking |

## Software & Services

- Proxmox
  └── Currently running Application Management Panel (AMP) to self-host game servers
- ZimaOS
  └──   - Tailscale
        - Immich
        - NFS / samba
        - NAS

### Personal Cloud
I use my NAS to store and access files across my devices.

### Remote Access
I use Tailscale to securely access services while away from home.

### Cyber Range
I am building an isolated lab environment where I can practice
cybersecurity and networking concepts.

## What I Learned
- Virtualization
- Networking
- NAS and NFS storage
- Docker containers
- Secure remote access
- Troubleshooting

## Future Plans
- Expand my cyber range
- Add more virtual machines
- Improve network segmentation
- Add monitoring and logging
- Migrating my NAS from ZimaOS to TruNAS
