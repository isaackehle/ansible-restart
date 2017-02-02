# Ansible Role - restart

Handle System Restart and wait for it to return

Available on Ansible Galaxy: [pgkehle.restart](https://galaxy.ansible.com/pgkehle/restart)

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
         - pgkehle.restart

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

Paul Kehle  
@pgkehle ([twitter](https://twitter.com/pgkehle), [github](https://github.com/pgkehle), [linkedin](https://www.linkedin.com/in/pgkehle))
