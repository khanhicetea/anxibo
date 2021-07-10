## An-Xi-Bo

Named **An-Xi-Bo** (Ansible sounds in Vietnamese), is IaC (Infrastructure as Code) tool replace for [lenmay](https://github.com/khanhicetea/lenmay) with python and bash script.

### Why ?

Ansible is more stable, consistent and active-maintained

### Stack

- LEMP (at the moment)

### LEMP

Install LEMP Stack

```
$ ansible-playbook lemp/lemp.yml
```

Create a new site

```
$ ansible-playbook lemp/site.yml
```

### LICENSE

MIT 2021