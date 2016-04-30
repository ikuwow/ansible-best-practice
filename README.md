# ansible-best-practice

Ansible best practice exercise

## Usage

```
$ vagrant up
```

```
$ ansible-playbook -i hosts_development site.yml
```

## Logs

```
$ ansible-galaxy install manala.timezone
- downloading role 'timezone', owned by manala
- downloading role from https://github.com/manala/ansible-role-timezone/archive/master.tar.gz
- extracting manala.timezone to /usr/local/etc/ansible/roles/manala.timezone
- manala.timezone was installed successfully
```

Or, after creating roles.yml, `ansible-galaxy install -r roles.yml`.


## References

> Best Practices — Ansible Documentation
> http://docs.ansible.com/ansible/playbooks_best_practices.html

> Ansible Galaxy | About
> https://galaxy.ansible.com/intro
