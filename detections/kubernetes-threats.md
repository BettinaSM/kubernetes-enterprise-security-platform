# Kubernetes Threat Detection

## Runtime Threat Examples

### Shell Execution Inside Container

Potential attacker activity involving interactive shell execution inside running containers.

### Privileged Container Abuse

Containers running with elevated privileges may increase attack surface.

### Suspicious Process Execution

Unexpected binaries or processes executed inside containers may indicate compromise.

## Detection Sources

- Falco runtime monitoring
- Kubernetes audit concepts
- SIEM correlation workflows
