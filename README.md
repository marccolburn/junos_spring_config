Segment Routing Configuration
=========

Configure Segment Routing for Junos.

Requirements
------------


Role Variables
--------------
mpls_interfaces: List of Dictionaries containing MPLS interfaces and unit
* name: string
* unit: int

spring_settings:
* start_label: string
* index_range: string
* node_id: string

Dependencies
------------

N/A

Example Playbook
----------------

    - hosts: all
      roles:
         - { role: junos_spring_config }

License
-------

BSD

Author Information
------------------

Marc Colburn Juniper
