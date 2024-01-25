# Linux Infrastructure Capstone – FameTech NYC

_A Sprint-Based Simulation of Real-World DevOps Engineering Tasks_

## Project Summary

This capstone simulates the day-to-day responsibilities of a Linux Infrastructure & DevOps Engineer at FameTech NYC, contracted to support CloudVerse Corp’s internal systems.

Spanning seven structured sprints, the project covers hybrid OS provisioning, secure access, CI/CD tooling, process monitoring, Bash scripting, DNS troubleshooting, and static IP configuration. Each sprint represents real-world enterprise scenarios aligned with DevSecOps, automation, and system reliability goals.

All tasks were executed on CentOS 7 and Ubuntu 22.04 virtual machines provisioned via Vagrant, and each deliverable follows enterprise DevOps practices—validated through command-line automation, documentation, and ticket-based workflows.

> Project experience is verifiable via FameTech NYC.

---

## Sprint Overview

| Sprint   | Title                                         | Focus                                                               |
| -------- | --------------------------------------------- | ------------------------------------------------------------------- |
| Sprint 1 | VM Provisioning & Access Hardening            | Vagrant setup, SSH security, sudo policies, user/group management   |
| Sprint 2 | Filesystem, Logs & Storage                    | Directory structuring, log permissions, archiving, loopback mounts  |
| Sprint 3 | CI/CD Software Installation & Service Control | Jenkins, Ansible, Apache installation, GPG keys, repo config        |
| Sprint 4 | Process Management & System Monitoring        | CPU/memory diagnostics, zombie handling, system recovery            |
| Sprint 5 | Bash Automation Toolkit                       | Script-based user creation, service health checks, backups          |
| Sprint 6 | Network Diagnosis & DNS Troubleshooting       | DNS resolution, port checks, name lookup, traceroute, hosts mapping |
| Sprint 7 | Static IP & Routing Configuration             | Netplan setup, DNS resolver config, persistent connectivity         |

---

## Tools & Technologies

- **Operating Systems**: Ubuntu 22.04, CentOS 7
- **Provisioning Tools**: Vagrant, VirtualBox
- **DevOps Software**: Jenkins, Apache HTTPD, Ansible
- **Package Managers**: APT, YUM, DNF, RPM
- **Monitoring & Process Control**: ps, top, journalctl, systemctl, cron
- **Scripting & Automation**: Bash, awk, xargs, functions, conditionals
- **Networking Tools**: ping, ss, telnet, dig, curl, traceroute, nslookup
- **Storage & Archiving**: tar, zip, mount, losetup, fstab

---

## Repository Layout

```

linux-infrastructure-automation-monitoring/
├── CV-LAB-001/
├── CV-LAB-002/
├── CV-LAB-003/
├── CV-LAB-004/
├── CV-LAB-005/
├── CV-LAB-006/
├── CV-LAB-007/
└── README.md

```

---

## Use Case Scenarios Simulated

- Secure VM bootstrapping for CI/CD environments
- Jenkins and Ansible deployment via custom repositories
- Monitoring system load and resolving service crashes
- Automating infrastructure tasks with Bash for Ops teams
- Debugging DNS resolution and unreachable services
- Assigning static IPs for VMs in non-DHCP private networks

---

## Credits

- **Project Design**: [Ariful Haq](https://github.com/akmarif) – Mentor & DevOps Architect
- **Execution**: [Sheikh Ahmed](https://github.com/sheikhiahmed) – DevOps Engineer (In Training)
- **Location**: NYC
- **Verification**: Project history verifiable via [FameTech NYC](https://fametech.nyc)

---

## Contact

- GitHub: [github.com/sheikhiahmed](https://github.com/sheikhiahmed)
- LinkedIn: [linkedin.com/in/sheikh-ahmed-sde](https://www.linkedin.com/in/sheikh-ahmed-sde)
- Project Verification: Available upon request

---

## License

This project is licensed under the [MIT License](https://opensource.org/licenses/MIT). See the [LICENSE](./LICENSE) file for details.

---
