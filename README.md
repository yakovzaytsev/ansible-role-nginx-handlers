Role Name
=========

Nginx handlers

Example Playbook
----------------

Add it to `yourrole/meta/main.yml` like this

    dependencies:
      - yakovzaytsev.nginx-handlers

Then in playbook like this

    - foo:
      ...
      notify:
        - restart nginx

License
-------

BSD
