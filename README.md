# ansible
---------

## Usage
Run updates but do not reboot
```bash
ansible-playbook apt-upgrade.yml
```

Run updates and rebooot if required (can be run after the previous command if you want to verify which servers will reboot)
```bash
ansible-playbook apt-upgrade.yml -e "reboot=True"
```
