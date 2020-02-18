Role for managing [s3 exporter](https://github.com/ribbybibby/s3_exporter) for prometheus  

Requires only settings AWS credentials:
```yaml
s3_exporter_aws_access_key_id: 0
s3_exporter_aws_secret_key: 0
```

Other parameters:
```yaml
s3_exporter_user: s3_exporter
s3_exporter_version: 0.3.0
s3_exporter_bind: ":9340"
s3_exporter_cli_flags: {}
```