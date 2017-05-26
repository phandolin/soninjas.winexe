#Ansible Role: soninjas.winexe

Ansible role to install exe files on remote Windows hosts using Powershell.

##Requirements

#Sample playbook file
--------------

    hosts: Windows

    vars_files:
      - "../roles/soninjas.winexe/vars/main.yml"

    roles:
         - role: soninjas.winexe
           tags: lamp

    hosts: Windows32

    vars_files:
      - "../roles/soninjas.winexe/vars/main.yml"

    roles:
         - role: soninjas.winexe
           tags: lamp


##Role Variables
--------------

Update the `vars/mail.yml` file with download-link, Program-Name and filename. Group hosts under Windows and Windows32 (for 32-bit)



##License
-------

BSD

##Author Information
------------------

Southern Oregon Net Ninjas contact: phil@southernoregonnetninjas
