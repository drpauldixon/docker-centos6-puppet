# CentOS 6 with puppet client

## Example builds

*puppet 3.7.3 (default):*

```
docker build -t reducible/centos6_puppet:3.7.3 .
docker push reducible/centos6_puppet:3.7.3
```

*puppet 3.7.5:*

```
version=3.7.5
docker build --build-arg VERSION=$version -t reducible/centos6_puppet:$version .
docker push reducible/centos6_puppet:3.7.5
```
