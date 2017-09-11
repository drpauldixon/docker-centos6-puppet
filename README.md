# CentOS 6 with puppet client

## Example builds

*puppet 3.7.3 (default):*

```
docker build -t centos-puppet:3.7.3 .
```

*puppet 3.7.5:*

```
version=3.7.5
docker build --build-arg VERSION=$version -t centos-puppet:$version .
```

---