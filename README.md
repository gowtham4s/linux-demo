# linux-demo
# 🐧 Linux Administration Skill Levels

A structured breakdown of Linux administration skills from foundational basics to production-grade DevOps capabilities.

---

## 🟢 Level 1 – Basic (Foundational Skills)

| Status | Skill                                         |
| ------ | --------------------------------------------- |
| ✔️     | Set up users and groups for development teams |
| ✔️     | Manage permissions for project directories    |
| ✔️     | Install required packages (git, nginx, java)  |
| ✔️     | Check system information (memory, CPU, disks) |

---

## 🟡 Level 2 – Intermediate (Daily DevOps Tasks)

| Status | Skill                                                                    |
| ------ | ------------------------------------------------------------------------ |
| ✔️     | Automate backups using Cron                                              |
| ✔️     | Create shell scripts for log cleanup, service restart, and health checks |
| ✔️     | Manage logs under `/var/log`                                             |
| ✔️     | Monitor system performance and troubleshoot services                     |

---

## 🔴 Level 3 – Advanced (Production-Ready Linux Admin)

| Status | Skill                                                 |
| ------ | ----------------------------------------------------- |
| ✔️     | Create custom `systemd` services for applications     |
| ✔️     | Apply SSH hardening for security                      |
| ✔️     | Set up LVM for storage scaling                        |
| ✔️     | Configure firewall rules (UFW / firewalld / iptables) |
| ✔️     | Implement `logrotate` for application logs            |

---

## 📂 Suggested Repository Structure

```
linux-admin-skills/
├── level-1-basic/
│   ├── user-management.md
│   ├── permissions.md
│   ├── package-installation.md
│   └── system-info.md
├── level-2-intermediate/
│   ├── cron-backups.sh
│   ├── log-cleanup.sh
│   ├── service-restart.sh
│   ├── health-check.sh
│   └── log-management.md
├── level-3-advanced/
│   ├── systemd-service-example.service
│   ├── ssh-hardening.md
│   ├── lvm-setup.md
│   ├── firewall-rules.md
│   └── logrotate-config.md
└── README.md
```

---