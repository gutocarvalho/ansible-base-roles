## Ansible base repo

This repo contains base roles for my personal use.

I use mostly to configure the VMs running in my personal ProxMox Cluster at home.

## Roles

### PreReq

- Install git
- Install common linux packages
- Install neofetch

### Users

- Creates and removes users
- Add ssh-key for users

### Proxmox-Agent

- Install qemu agent for proxmox VMs

## How to use it?

Clone the repo and enter the directory

    $ git clone git@github.com:gutocarvalho/ansible-base-roles.git
    $ cd ansible-base-roles

Run the main playbook

    $ ansible-playbook main.yaml -i inventory/via

That's all folks!
