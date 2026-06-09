# Troubleshooting Log



## Issue 1

Problem: DC02 couldn't find corp.local domain

Cause:   DNS not pointing to DC01

Fix:     Set DNS to 192.168.10.10 on DC02



## Issue 2

Problem: VMs couldn't communicate

Cause:   Different VMware networks

Fix:     Moved both VMs to VMnet1



## Issue 3

Problem: Replication failing

Cause:   Outbound replication disabled

Fix:     repadmin /syncall /AdeP

