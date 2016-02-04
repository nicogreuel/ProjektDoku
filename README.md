# ProjektDoku
### Paketupdate
 
     apt-get update
     apt-get install nano


### Admin user hinzufügen

    aduser admin

change sudo rights in /etc/sudoers

## create SSH dir and add keys

    mkdir ~/.ssh
    chmod 0700 ~/.ssh
    touch ~/.ssh/authorized_keys
    chmod 0644 ~/.ssh/authorized_keys
    sudo nano ~/.ssh/authorized_keys

create keys with puttygen and add public key to authorized_keys

## deny SSH root login in sshd.config
