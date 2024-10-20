# Puppet Installer

This repository contains a script to install Puppet on a variety of systems easily. Puppet is an open-source configuration management tool that allows you to automate the provisioning, configuration, and management of your infrastructure.

## Installation

To quickly install Puppet using this script, you can run the following command:

```bash
curl -sfL -o /tmp/install_puppet.sh https://raw.githubusercontent.com/faynlab/puppet-installer/refs/heads/master/install_puppet && \
    chmod +x /tmp/install_puppet.sh && \
    puppet_version=8 \
    /tmp/install_puppet.sh
```

## Notes
- **Supported OS**: Currently, this script supports **Ubuntu** only.
- Compatibility with other Linux distributions or operating systems may be added in future updates.
