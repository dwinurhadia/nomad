# Oprek Bareng

## Requirements

1. Install Visual Studio Code

1. Install Remote SSH Extension (https://marketplace.visualstudio.com/items?itemName=ms-vscode-remote.remote-ssh)

## Starting the lab

1. Generate SSH Config from vagrant

```
vagrant ssh-config > ssh_config
```

### Command:

### SSH Copy
ssh-copy-id -i /home/d/.ssh/id_rsa.pub d@node-2
ssh-copy-id -i /home/d/.ssh/id_rsa.pub d@node-3
ssh-copy-id -i /home/d/.ssh/id_rsa.pub d@node-1
