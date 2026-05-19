# Platform Architecture

## Components

| Component | Purpose |
|---|---|
| Kubernetes | Container orchestration |
| RBAC | Access governance |
| Falco | Runtime threat detection |
| SIEM | Security event monitoring |
| MITRE Mapping | Threat classification |
| Network Policies | Traffic segmentation |

## Security Flow

Container Activity
        ↓
Falco Detection
        ↓
Security Alert
        ↓
SIEM Correlation
        ↓
MITRE Classification
        ↓
Incident Investigation
