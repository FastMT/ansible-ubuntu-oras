# ansible-ubuntu-oras
Ansible role to install ORAS on linux (Ubuntu) server


ORAS is cli tool to store any binary files in container registries - https://oras.land/


## Installation

Create requirements.yml file

```
# Include ubuntu-oras role
- src: https://github.com/FastMT/ansible-ubuntu-oras.git
  name: ubuntu-oras
  version: "v1.0.1"
```

Install external module into ~/.ansible/roles folder

```
ansible-galaxy install -r requirements.yml
```

## Usage

playbook.yml:

```
# Install ORAS
- role: "ubuntu-oras"
```   
