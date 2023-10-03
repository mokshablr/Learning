# Why virtualenv?

It doesn't install packages globally in your system.

## How to create a venv:
- Create a venv: `virtualenv env` (doesn't have to be env)
- Activate the env: `source env/bin/activate`

Installed packages(dependencies) get saved into this env folder.

## Security:
It minimizes the risk of accidentally modifying or deleting critical system packages.

## Cleaner and More Portable Code:
When sharing the project, the packages installed will also be shared!