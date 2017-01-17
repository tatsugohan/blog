# Usefull linux command

listing of configured repository

>dnf repolist

```
[root@localhost ~]# dnf repolist
Vérification de l'expiration des métadonnées effectuée il y a 0:22:42 sur Tue Jan 17 23:23:33 2017.
id du dépôt                 nom du dépôt                                  statut
*fedora                     Fedora 25 - x86_64                            51 669
google-chrome               google-chrome                                      3
*rpmfusion-free             RPM Fusion for Fedora 25 - Free                  541
*rpmfusion-free-updates     RPM Fusion for Fedora 25 - Free - Updates        133
*rpmfusion-nonfree          RPM Fusion for Fedora 25 - Nonfree               169
*rpmfusion-nonfree-updates  RPM Fusion for Fedora 25 - Nonfree - Updates      36
*updates                    Fedora 25 - x86_64 - Updates                  14 725
```

add external repository

> dnf install https://download1.rpmfusion.org/free/fedora/rpmfusion-free-release-$(rpm -E %fedora).noarch.rpm 
> dnf install https://download1.rpmfusion.org/nonfree/fedora/rpmfusion-nonfree-release-$(rpm -E %fedora).noarch.rpm

