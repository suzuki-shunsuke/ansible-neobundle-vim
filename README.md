neobundle-vim
===============

Install [neobundle.vim](https://github.com/Shougo/neobundle.vim).

Requirements
------------

* ghq

Role Variables
--------------

* neobundle_vim_ghq_executable: The executable path of ghq command. The default is "ghq".

Dependencies
------------

* [suzuki-shunsuke.ghq-module](https://galaxy.ansible.com/suzuki-shunsuke/ghq-module/)

Example Playbook
----------------

```yaml
- hosts: servers
  roles:
  - suzuki-shunsuke.neobundle-vim
```

License
-------

MIT
