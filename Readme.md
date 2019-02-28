# katello-ansible-seeds

## Configure

```sh
cp server_vars.yml.example server_vars.yml
cp seed.yml.example seed.yml

vim server_vars.yml
vim seed.yml # customize or use as is
```

## Setup

```sh
ansible-playbook setup.yml
```

## Seed

```sh
ansible-playbook seed.yml
```
