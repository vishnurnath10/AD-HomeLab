 Lab Network Plan



## IP Addressing

| Device   | IP             | Role        |

|----------|----------------|-------------|

| DC01     | 192.168.10.10  | Primary DC  |

| DC02     | 192.168.10.11  | Secondary DC|

| CLIENT01 | DHCP auto      | Workstation |



## Subnet

- Network: 192.168.10.0/24

- Mask: 255.255.255.0

- DHCP Pool: 192.168.10.100 - .200

- Reserved: 192.168.10.1 - .99



## Domain

- Name: corp.local

- Forest Level: Windows Server 2016

\- DSRM Password: documented securely offline

