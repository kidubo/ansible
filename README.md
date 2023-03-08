# Ansible

First You'll need to install Ansible here are the steps

 `$ sudo apt update`
 `$ sudo apt upgrade -y`
 `$ sudo reboot`

 ```
     sudo apt install -y software-properties-common
     sudo add-apt-repository --yes --update ppa:ansible/ansible

     sudo apt update
     sudo apt install -y ansible
     ansible --version

 ```

 `ansible-playbook -t node ansible.yaml`  This is installing by tags
 `ansible-playbook -t zsh ansible.yaml`  This is installing by tags
 
 You may need to copy the .ssh folder from your older pc here is the link on how to Do it.
### Easiest method to Copy SSH Keys of One machine to another machine in Linux
https://readybytes.in/blog/easiest-method-to-copy-ssh-keys-of-one-machine-to-another-machine-in-linux
