# Almaz Bastamiev

Network engineer from Astana, Kazakhstan. 6+ years in multi-vendor enterprise and
critical-infrastructure networks. I run networks the NetOps way: device APIs instead of
click-ops, configuration as code, automated backups and monitoring, and AI agents that
work with firewalls and routers under strict guardrails.

Open to NetOps / Network Automation roles, relocation or remote.

## What I work with

- **Security:** Palo Alto (PAN-OS, GlobalProtect), FortiGate NGFW, IPsec and SSL VPN
- **Routing and switching:** BGP, OSPF, VRF / L3VPN, VRRP; Cisco, Extreme, FortiSwitch, MikroTik
- **Automation:** Python, Ansible, Terraform, REST / XML APIs, MCP, Git
- **Platform:** Linux, Docker, Kubernetes, Proxmox, AWS (VPC, EC2, Bedrock)
- **Monitoring:** Zabbix, LibreNMS, Grafana, SNMPv3, syslog

## Projects

| Repository | What it does |
|---|---|
| [panos-mcp](https://github.com/diamond973/panos-mcp) | MCP server for Palo Alto PAN-OS / Panorama. Lets an AI agent read configs, logs and sessions, and make changes only in write mode, with a backup and partial commit. |
| [mikrotik-mcp](https://github.com/diamond973/mikrotik-mcp) | MCP server for MikroTik RouterOS over the binary API (works on v6 and v7). Read-only by default; ping, traceroute, routes, firewall, backups. |
| [pfsense-to-fortigate-migration](https://github.com/diamond973/pfsense-to-fortigate-migration) | Case study: moving a ~15-office company from pfSense to FortiGate 70G together with a datacenter move. Plan, cutover over two WANs, rollback, and the problems hit along the way. |

The MCP servers are single Python files with no dependencies outside the standard library.

## Contact

- LinkedIn: [linkedin.com/in/almazbastamiev](https://www.linkedin.com/in/almazbastamiev)
- Email: almaz.bastamiev2501@gmail.com
