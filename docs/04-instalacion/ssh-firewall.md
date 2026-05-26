# SSH y Firewall

## SSH

```bash
sudo apt install openssh-server
```

## Reglas UFW

```bash
ufw allow from 192.168.1.0/24 to any port 22
ufw allow 80/tcp
ufw allow 443/tcp
```