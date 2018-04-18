# Installs gitg and configures UI tools on a desktop

Installs gitg and meld, then configures meld as default UI merge tool

## Requirements

Git installed and configured, see https://github.com/mashimom/git-config

## Role Variables

None.

## Dependencies

No dependencies.

## Example Playbook

    ---
    - hosts: localhost
      roles:
         - role: git-gui-tools

## License

MIT

# Author Information

@mashimom