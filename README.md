# SOHO Network Project in Cisco Packet Tracer

This project is a Small Office / Home Office (SOHO) network built in Cisco Packet Tracer with VLANs, router-on-a-stick, DHCP, and wireless connectivity.

## Project Overview
Three departments: Admin, Finance, Reception in separate VLANs with router-on-a-stick inter-VLAN routing and DHCP.

## VLAN and IP Plan

| Department | VLAN | Network | Gateway |
| Admin      |  10  | 192.168.10.0/26 | 192.168.10.1 |
| Finance    |  20  | 192.168.10.64/26 | 192.168.10.65 |
| Reception  |  30  | 192.168.10.128/26 | 192.168.10.129 |

## Skills Demonstrated
- VLAN configuration
- Inter-VLAN routing (router-on-a-stick)
- DHCP pools
- Wireless setup
- IP subnetting
- Network troubleshooting

## Files
- `soho-network-project.pkt` - Cisco Packet Tracer file
- `router-config.txt` - Router configuration
- `switch-config.txt` - Switch configuration

## How to Upload to GitHub
1. Go to github.com → New repository
2. Name: SOHO-Network-Project
3. Choose Public, add README
4. Add file → Upload files
5. Drag entire folder
