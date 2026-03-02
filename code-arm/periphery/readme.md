Firewall

```bash
ufw status | grep -q inactive && ufw --force enable
ufw status
ufw allow from 46.62.248.95 to any port 8120 proto tcp
ufw reload
```

Python

```bash
sudo apt update
sudo apt install python3
```
