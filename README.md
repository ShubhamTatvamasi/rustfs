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

