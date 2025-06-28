# Task 4 — Firewall Configuration using UFW

## Objective
Set up and test basic firewall rules on Ubuntu using UFW.

## Steps Taken
- Listed current rules
- Blocked port 23 (Telnet)
- Allowed port 22 (SSH)
- Verified and removed rules

## Commands Used
```bash
sudo ufw status
sudo ufw deny 23
sudo ufw allow 22
sudo ufw status numbered
sudo ufw delete <rule-number>
sudo ufw enable
