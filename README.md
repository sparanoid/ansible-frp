# ansible-frp
Ansible role for frp

## Install

```shell
git submodule add https://github.com/sparanoid/ansible-frp roles/sparanoid.frp
```

Create your own frpc/frps configs under:

- `{{ inventory_dir }}/files/frp/{{ inventory_hostname }}/{{ frpc_conf }}`
- `{{ inventory_dir }}/files/frp/{{ inventory_hostname }}/{{ frps_conf }}`
