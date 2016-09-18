# mac-provisionning-playbook
Scripts to bootstrap my development environnement on a new mac machine with ansible

```
curl --remote-name https://raw.githubusercontent.com/jumichot/mac-provisioning-playbook/master/bootstrap.sh
less mac
sh bootstrap.sh 2>&1 | tee ~/laptop.log
```

Then :
```
git clone https://github.com/jumichot/mac-provisioning-playbook.git
cd mac-provisioning-playbook
ansible-playbook laptop.yml -K
```


##Manual installs
- Load licences into paid apps : istat, bettertouchtool, bartender, hazzel

##TODO
- tmuxinator
- custom zsh plugins
- solarized


