# Exercise 4 - UFW Firewall

## VPS

- Provider: CloudIX
- OS: Ubuntu Server 24.04.1 LTS
- Public IP: 180.93.125.129

## UFW Configuration

Default incoming policy:

deny

Default outgoing policy:

allow

## Allowed Inbound Ports

- TCP 22 - SSH
- TCP 80 - HTTP

## Verification

Command:

```bash
sudo ufw status verbose