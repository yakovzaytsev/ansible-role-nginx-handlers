Role Name
=========

Nginx handlers

Example Playbook
----------------

Add it to `yourrole/meta/main.yml` like this

    dependencies:
      - ysz.nginx_handlers

Then in playbook like this

    - foo:
      ...
      notify:
        - restart nginx

License
-------

BSD
