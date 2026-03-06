# homelab-learning-journal
A documentation of my homelab including: architecture, configs, troubleshooting notes
The goal is to build a practical environment for learning Linux, networking, automation, security, and systems engineering.

## Homelab overview
### Hardware ###
- Raspberry pi 4B (pi OS)
- (Mini pc) AOOSTAR GEM12 MAX (Planned)

### Services
- Adguard Home - DNS fronted, filtering, metrics
- Unbound - recursive DNS backend
- Monitoring (prometheus + grafana) (planned)
- containerisation (Docker) (planned)
- Jellyfin - self-hosting media servers for movies and shows (planned)
- Personal datastore - local storage for documents (planned)
- File syncing (planned)
- containerised services (planned)

## Current architecture
[ Clients ] -> [ AdGuard Home ] -> [ Unbound ] -> [ Root DNS Servers ]
- AdGuard handles DNS queries from devices on the network  
- Unbound performs secure recursive resolution  
- Services run locally for privacy, speed, and control
A more detailed diagram will be added in '/diagrams'

## Long term goals
As the homelab grows I plan to experiment with:
- ai workloads such as training simple AI agents locally (reinforcemnt learning, small models, automation)
- Build small environments for data processing
