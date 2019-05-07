# Fix pkg on FreeNAS 11.2

I was unable to run pkg with an error about being unable to find the local repo file.

pkg: Repository local load error: access repo file(/var/db/pkg/repo-local.sqlite) failed: No such file or directory

```
[root@freenas ~]# pkg install ca_root_nss
Updating local repository catalogue...
pkg: Repository local load error: access repo file(/var/db/pkg/repo-local.sqlite) failed: No such file or directory
pkg: file:///usr/ports/packages/meta.txz: No such file or directory
repository local has no meta file, using default settings
pkg: file:///usr/ports/packages/packagesite.txz: No such file or directory
Unable to update repository local
Error updating repositories!
```

This can be fixed by editing the configuration files in /usr/local/etc/pkg/repos/, setting toggling the “enabled” parameter to “no” for local.conf and to “yes” for FreeBSD.conf.

```
sed 's/enabled: yes/enabled: no/' /usr/local/etc/pkg/repos/local.conf
sed 's/enabled: no/enabled: yes/' /usr/local/etc/pkg/repos/FreeBSD.conf

```
You should now be able to install and update using pkg.
