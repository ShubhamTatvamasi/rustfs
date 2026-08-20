# rustfs

list all buckets:
```bash
aws s3 ls
```

create a test file:
```bash
echo "Hello RustFS" > test.txt
```

Upload the file:
```bash
aws s3 cp test.txt s3://test-bucket/
```

list files:
```bash
aws s3 ls s3://test-bucket/
```

delete local file:
```bash
rm test.txt
```

download file:
```bash
aws s3 cp s3://test-bucket/test.txt .
```
