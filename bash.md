## Arch

# reset package manager

```
sudo killall pamac-updater
sudo rm /var/lib/pacman/db.lck
```

# ssh

```
eval "$(ssh-agent -s)"
ssh-add ~/.ssh/id_rsa
```
