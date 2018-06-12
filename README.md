# HLOS Orchestration files

Everything regarding management of the HLOS platform. Ansible is used.

# #Setup

1. Maak admin user aan op openstack
2. Installeer Ansible op een lokaal systeem (moet mogelijk Linux zijn)
3. Maak orchestration-manager aan (Ansible; evt. op een docker host)
4. Kopieer de benodigde systemen (ie. automatic git clone oid)
5. Vanaf orchestration-manager; zet het netwerk op

## Notes

- metadata 'group' vertaalt zich automatisch naar Ansible groep wanneer je openstack.py gebruikt voor Dynamic Inventory
- 
