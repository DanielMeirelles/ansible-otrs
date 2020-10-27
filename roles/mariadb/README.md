[![Build Status](https://travis-ci.org/uniQconsulting-ag/ansible.mariadb.svg?branch=master)](https://travis-ci.org/uniQconsulting-ag/ansible.mariadb)

[![Alt text](https://www.uniqconsulting.ch/images/logo.png)](https://www.uniqconsulting.ch/)


MariaDB Setup with Ansible
=================

* install and configure MariaDB

Requirements
------------

* Currently only tested with CentOS 7
* Ansible 2.4 or higher is required for this Ansible Role

Role Variables
--------------
Variables are self speaking or documented in:   
* `defaults/main.yml`
* `vars/main.yml`

The following variables can be overridden:
 * `mariadb_secure_installation`: Default: false. Similar to `mysql_secure_installation`
 * `mariadb_root_password`: Default: ''.
 * `mariadb_databases`: Default: {} . Dictionary with databases.
 * `mariadb_users_create`: Default: {}. Dictionary with user credentials.
 * `mariadb_users_remove`: Default: {}. Dictionary of users to remove.

Dependencies
------------

This Ansilbe Role has no dependencies to other Ansilbe Roles

Example Playbook
----------------

Example playbooks for this role are located in ´test´ folder:
* `test/playbook_mariadb_minimal.yml`: Minimal role for testing
* `test/playbook_mariadb.yml`: Real life example
* `test/playbook_mariadb_full.yml`: Full example with all possible vars.  

uniQconsulting ag
-----------------

uniQconsulting ag is an IT consulting company with headquarters in Bassersdorf, Switzerland and a wholly owned subsidiary of Netcloud AG since 2017.
Netcloud is a privately held company, reputed for Network and Cloud Services in Switzerland. Although operating independently, both companies have a long history of close collaboration.

uniQconsulting provides a wide range of IT services from the datacenter to the edge and the cloud. The services and solutions of uniQconsulting are well established among clients in business areas like financial services, health care, the public sector and medium sized enterprises.

Depending on individual client requirements, uniQconsulting can assume responsibility for selected, or for all phases of a project. Highly certified and experienced staff guarantee successful implementations. Projects are monitored from start to finish. 

Once a project has been successfully completed, comprehensive services are available to the customer. Our trilingual Expert Helpdesk, based in Switzerland, can take on specific tasks, offloading the client staff, or proactively monitor the IT infrastructure, responding appropriately in the event of an incident or pending change. This gives customers the certainty of being able to call on the appropriate specialist if necessary, without having to build up this know-how internally.

By outsourcing services related to the IT infrastructure, customers can focus on business-applications and processes, resulting in greater transparency and financial predictability in IT operations. The experts at uniQconsulting help customers to create a long-term IT strategy, supporting their overall business goals.

Compliance and security topics are becoming increasingly complex and expensive. Not shying away from thinking outside the box, uniQconsulting focusses on designing high quality and game-changing IT Solutions, with the specific goal of optimizing efficiency and security in digital workflows while maximizing ROI.

We believe in IT-driven success.

License
--------------
https://opensource.org/licenses/LGPL-3.0    
Copyright (c) uniQconsulting ag - Chris Ruettimann <cruettimann@uniqconsulting.ch>
