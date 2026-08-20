# AWS

Install `aws` cli:
```bash
brew install awscli
```

---

Generate Access Key ID:
```bash
openssl rand -base64 32 | tr -dc 'A-Z0-9' | head -c 20; echo
```

Generate Secret Access Key:
```bash
openssl rand -base64 64 | tr -dc 'A-Za-z0-9' | head -c 40; echo
```

---

Config your key:
```bash
aws configure
```

```
AWS Access Key ID [None]: 898384F352206C8BA82C
AWS Secret Access Key [None]: UMmJZtaQKcloqgfMmB8IgDjOK88Hu5E82lB3yRQR
Default region name [None]: us-east-1
Default output format [None]:
```

---

```bash
vim ~/.aws/config
```

```
[default]
region = us-east-1
endpoint_url = https://rustfs.k8s.shubhamtatvamasi.com
```

---


```bash
vim ~/.aws/credentials
```

```
[default]
aws_access_key_id = 898384F352206C8BA82C
aws_secret_access_key = UMmJZtaQKcloqgfMmB8IgDjOK88Hu5E82lB3yRQR
```




