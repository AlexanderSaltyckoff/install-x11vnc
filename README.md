# install-x11vnc
The playbook installs the remote vnc connection daemon.

To use it, just set the hosts file in the configuration you want and start the playbook.

The default password is 12345678, but you can change it in the install-x11vnc/roles/install_x11/tasks file
/main.yml on line 21.

The playbook also sets the ip for the connection based on the {{ ansible_ssh_host }} variable.
