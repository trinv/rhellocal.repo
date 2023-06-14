## rhellocal.repo
Mount ISO
```
mount -t iso9660 /dev/sr0 /mnt
```
Add local repo file
```
vi /etc/yum.repos.d/rhellocal.repo
[LocalRepo]
name=LocalRepository
baseurl=file:///mnt
enabled=1
gpgcheck=0
```
