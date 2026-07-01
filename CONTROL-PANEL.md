# Control Panel System Development Scope (Updated OS Support)
## Enterprise Open-Source Hosting, Infrastructure & DevOps Control Panel

---

# Operating System Support Matrix

The control panel must support a wide range of production-grade Linux distributions used in hosting, enterprise infrastructure, and cloud environments.

## Fully Supported Operating Systems

### Ubuntu LTS

- Ubuntu 20.04 LTS
- Ubuntu 22.04 LTS
- Ubuntu 24.04 LTS
- Ubuntu 26.04 LTS (forward compatibility target)

### Debian Stable

- Debian 11 (Bullseye)
- Debian 12 (Bookworm)
- Debian Stable future releases (forward-compatible design required)

### RedHat Enterprise Linux (RHEL)

- RHEL 8
- RHEL 9
- RHEL 10

### AlmaLinux

- AlmaLinux 8
- AlmaLinux 9
- AlmaLinux 10

### Rocky Linux

- Rocky Linux 8
- Rocky Linux 9
- Rocky Linux 10

### CloudLinux

- CloudLinux 8
- CloudLinux 9
- CloudLinux 10

---

# OS Abstraction Layer Requirements

The platform must implement a **unified OS abstraction layer** to ensure all provisioning logic is independent of underlying Linux distribution differences.

## Core Design Principles

- OS-agnostic application layer
- OS-aware provisioning layer
- Version-aware compatibility mapping
- Safe fallback execution strategies

---

## Unified System Interfaces

### Package Management Abstraction

- Debian-based systems:
  - `apt`
- RHEL-based systems:
  - `dnf` / `yum`

All package operations must be abstracted behind a unified API:

- install packages
- remove packages
- update packages
- repository management

---

### Service Management

- Standardised use of `systemd`
- Unified service lifecycle API:
  - start
  - stop
  - restart
  - reload
  - enable
  - disable

---

### Firewall Abstraction

- Ubuntu / Debian:
  - `ufw`
- RHEL / AlmaLinux / Rocky / CloudLinux:
  - `firewalld`

Optional advanced support:

- CSF (CloudLinux environments)
- nftables abstraction layer (future-proofing)

---

### Filesystem & Config Layer

- OS-specific configuration mapping layer
- Standardised service config registry
- Predictable path resolution abstraction

---

### OS Detection Engine

The installer and provisioning system must:

- Automatically detect OS and version
- Apply correct provisioning strategy
- Map compatible features dynamically
- Prevent unsupported configuration execution

---

# Hosting Stack Compatibility Per OS

## Web Servers

- NGINX (all supported OS)
- Apache HTTP Server (all supported OS)
- LiteSpeed / OpenLiteSpeed (where supported)

---

## DNS Systems

- BIND9 (all OS)
- PowerDNS (recommended for enterprise and RHEL-based systems)

---

## Email Stack

- Postfix (all OS)
- Dovecot (all OS)
- Rspamd / SpamAssassin (all OS)

---

## Database Systems

- MariaDB / MySQL (all OS)
- PostgreSQL (all OS)
- Redis (all OS)

---

## Security Systems

- Fail2ban (all OS)
- SELinux compatibility layer (RHEL / AlmaLinux / Rocky / CloudLinux)
- AppArmor support (Ubuntu / Debian)
- CSF firewall (CloudLinux optional integration)

---

## CloudLinux Enhancements

When CloudLinux is detected, the system must enable:

- LVE Manager integration
- CPU / RAM / IO resource limits per user
- CageFS isolation support
- Shared hosting hardening features
- Account-level resource enforcement

---

# Enterprise Infrastructure Support Targets

The control panel must be capable of operating in:

- Shared hosting environments
- Dedicated server environments
- VPS infrastructure
- Hybrid cloud deployments
- Kubernetes clusters
- Docker-based infrastructure
- Enterprise bare-metal data centers

---

# Testing Requirements (OS Compatibility)

## System-Level Validation Tests

- Installation tests across all supported OS versions
- Package manager compatibility verification
- Service lifecycle validation
- Network stack validation per OS

---

## Provisioning Tests

- Virtual host provisioning across OS types
- Email provisioning consistency tests
- DNS provisioning consistency tests
- Database provisioning validation across distributions

---

## Security & Hardening Tests

- Firewall compatibility validation (ufw/firewalld)
- SELinux enforcement validation (RHEL family)
- AppArmor policy validation (Ubuntu/Debian)
- SSH hardening validation
- Privilege escalation prevention tests

---

# Strategic OS Compatibility Vision

The control panel is designed to be:

- Fully OS-agnostic at the application layer
- Dynamically adaptive at the provisioning layer
- Enterprise-grade across all major Linux hosting distributions

This ensures seamless deployment across:

- Modern cloud environments
- Traditional hosting providers
- Enterprise IT infrastructures
- Kubernetes-native systems
- Hybrid multi-OS fleets

---

# Long-Term Platform Guarantee

This system is designed with forward compatibility for:

- Ubuntu LTS future releases
- RHEL enterprise lifecycle updates
- AlmaLinux/Rocky Linux ecosystem continuity
- CloudLinux hosting ecosystem evolution

ensuring long-term stability for enterprise-grade infrastructure deployments.
