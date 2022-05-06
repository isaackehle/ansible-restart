# Ansible Role - restart

Handle System Restart and wait for it to return

Available on Ansible Galaxy: [isaackehle.restart](https://galaxy.ansible.com/isaackehle/restart)

This role will restart a system and wait for it to come back

## Requirements

None

## Role Variables

NA

## Dependencies

None

## Example Playbook

    - hosts: all
      roles:
         - isaackehle.restart

## Hacking

There is an included Vagrant setup for hacking on this module, but IP needs to be set.

```
cd tests
source .hack.sh
vagrant up
ansible-playbook test.yml
...
vagrant destroy
vagrant up
ansible-playbook test.yml -vvvv
...
```

## License

MIT

## Author Information

Isaac Kehle
@isaackehle ([twitter](https://twitter.com/isaackehle), [github](https://github.com/isaackehle), [linkedin](https://www.linkedin.com/in/isaackehle))
