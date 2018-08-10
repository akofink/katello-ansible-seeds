# katello-devel-seeds

## Configure

```sh
cp server_vars.yml.example server_vars.yml
vim server_vars.yml
```

## Setup

```sh
ansible-playbook setup.yml
```

## Seed

```sh
ansible-playbook seed.yml
```
