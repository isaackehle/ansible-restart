# Ansible Role - restart

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

```
cd tests
source .hack.sh
vagrant up
ansible-playbook test.yml
...
```

## License

BSD

## Author Information

Paul Kehle  
@pgkehle (twitter, gmail, github, linkedin)
