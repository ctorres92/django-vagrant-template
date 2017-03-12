# django_vagrant_template
A template for a Django project using Vagrant, Ansible and PostgreSQL.

To configure:

1. Configure your variables in `__provision__/group_vars/development.yml`
2. Configure the name of your project in `Vagrantfile`
3. Configure your database settings according to the first step in `project/settings.py`

To run:

1. `vagrant up`
2. `vagrant ssh`
3. `cd /vagrant`
4. `python3 manage.py createsuperuser`
