Role Name
=========

This role installs supervisord and configures a process for a provided command.

Requirements
------------

None.

Role Variables
--------------

Available variables are listed below, along with default values (see `vars/default.yml`):

    supervisor_command: echo 'success!'

The command that should be run by the supervised process.

    supervisor_directory: /bin

The directory in which the command should be run

    supervisor_env:
        PATH=$PATH:/some/path

The environment that the command should run with.

    supervisor_numproces: 1

The number of processes to run the command with

    supervisor_process_name: echo_process

The name of the supervised process

Example Playbook
----------------

TODO

License
-------

MIT

Author Information
------------------

written by Justin Caratzas <jcaratzas@mnn.com> for Mother Nature Network
