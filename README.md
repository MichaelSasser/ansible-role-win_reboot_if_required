# michaelsasser.win-reboot-if-required

Reboot MS Windows if the required flag on Windows is set.

## Role Variables

| Varibale       | Default | Description                                                                             |
|----------------|---------|-----------------------------------------------------------------------------------------|
| reboot_timeout | 600     | The maximum time in seconds to wait for machine to re-appear on the network and respond |

## Example Playbook

```yaml
- hosts: all
  become: true
  roles:
    - michaelsasser.win-reboot-if-required
```

## License

Copyright &copy; 2020 Michael Sasser <Info@MichaelSasser.org>. Released under
the GPLv3 license.
