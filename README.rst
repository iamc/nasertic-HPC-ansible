#########################################
nasertic Ansible and Vagrant HPC tutorial
#########################################

Files for the introduction to Ansible and Vagrant in the context of a
HPC/OpenHPC tutorial.


:01-vagrant-centos7: Bare minimal (oficial) CentOS/7 Vagrant file.

:02-vagrant-OpenHPC-master: Minimal CentOS/7 OpenHPC head node Vagrant file, as used in the OpenHPC hands-on tutorial.

:03-vagrant-OpenHPC-bare: Three VirtualBox machines which can be used for an
                          OpenHPC test deploy: a master node and two pxe empty
                          machines. As pxe machines have no OS, they sould be
                          "vagrant up'ed" separately as vagrant "fails" on
                          them.

:04-vagrant-Ansible-hands-on: One head node plus two computing nodes for
                              ansible testing. Ansible is used first as Vagrant
                              provisioner, and also inside the `headnode` for
                              later computing nodes configuration.
