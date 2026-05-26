# SSH y Firewall

## SSH

```bash
sudo apt install openssh-server
```

## Reglas UFW

```bash
sudo ufw default deny incoming
sudo ufw default allow outgoing
sudo ufw allow OpenSSH
sudo ufw allow 80/tcp
sudo ufw allow 443/tcp
sudo ufw enable
```