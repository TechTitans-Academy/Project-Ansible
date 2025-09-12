# Ansible Small Project

Ansible project that will install the docker pacakge and run the TechTitans Dinner Application. We are creating two roles `docker` and `docker_container`.


### Project structure:

```
.
├── inventory.yml
├── playbook.yml
└── roles
    ├── docker
    │   └── tasks
    │       └── main.yml
    └── docker_container
        ├── tasks
        │   └── main.yml
        └── vars
            └── main.yml
```

### How to Run.

`#ansible-playbook -i inventory.ini playbook.yml`
