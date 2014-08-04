ansible-train
=============

Ansible provisioning playbook for deploying the [train controller](https://github.com/JonathanPorta/train) onto a RaspberryPi running Pidora.


## Development - running on an F20 Vagrant box.
`ansible-playbook -i development train.yml`

## Production - Pidora running on a Raspberry Pi B+
`ansible-playbook -i production train.yml`
