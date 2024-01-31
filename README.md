# pkg_check

## Datasource

### RPM

#### CMD

```
yum list -q --showduplicates {package}
```

#### KOJI

- https://koji.fedoraproject.org/koji/
- https://kojihub.stream.centos.org/koji/
- https://koji.mbox.centos.org/koji/
- https://koji.rockylinux.org/koji/

### DEB

#### CMD

```
apt-get changelog {package}
```

```
zcat /usr/share/doc/{package}//changelog.Debian.gz
```

#### Web

- https://launchpad.net/ubuntu/+source/{package}/+publishinghistory
- https://launchpad.net/debian/+source/{package}/+publishinghistory
