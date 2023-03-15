# ansible-role-locales

Ansible role to manage the system locales


## Requirements

    None


## Dependencies

    None


## Role Variables

    * locales_lang

    The default language setting for this system

    (default: en_US.UTF-8)

    * locales_locales

    Array of locales to be installed

    (default: [ en_US.UTF-8 UTF-8 ])


## Example Playbook

    ```yaml
    ---
    - hosts: all

      roles:
          - foolean/locales
    ```


## Supported Operating Systems

    * Debian (11)
    * Raspbian (11)
    * RedHat (8)
    * Rocky (8)


## License

    BSD-3-Clause
