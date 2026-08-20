# rustfs

Generate Access Key ID:
```bash
openssl rand -hex 10 | tr '[:lower:]' '[:upper:]'
```

Generate Secret Access Key ID:
```bash
openssl rand -base64 30
```
