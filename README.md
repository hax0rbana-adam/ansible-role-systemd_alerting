A simple role to get an email when any systemd service fails.

# Examples
## Playbook
Here's an example of a playbook to apply this role.

```yaml
- hosts: all
  become: true
  remote_user: root
  roles:
    - role: hax0rbana_adam.systemd_alerting
```

# Official repo location
All activity takes place on the official GitLab instance:
[https://gitlab.hax0rbana.org/public-repos/ansible/ansible-role-systemd_alerting](https://gitlab.hax0rbana.org/public-repos/ansible/ansible-role-systemd_alerting)

Any other hosting providers, such as GitHub.com and GitLab.com, are just mirrors
and we do not monitor the issue trackers over there.

# Support
## Matrix channel
You can also join our Matrix channel: #ansible:hax0rbana.org

This is a good place to ask questions or make requests without having to sign
up for another account.

# Contributing
See [contributor guidelines](CONTRIBUTING.md).

# License
This project is licensed under MIT License. See [LICENSE](LICENSE) for more details.
