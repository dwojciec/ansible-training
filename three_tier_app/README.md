# three tier app CI/CD for Mizi telecom
- date: 2017.12.25

## Basic Requirement
- git repository: https://github.com/hatsari/ansible-training/tree/master/three_tier_app
- Playbooks to deploy internal 3-tier app
- Install HA Ansible Tower

## Provision QA Environment (Including smoke test)


## Provision Production Environment (Including smoke test)

## Ansible Tower Workflow Templates

-----
below is the detailed explaination for each playbook.

- osp_configure_3tier.yml[osp_configure_3tier.yml]
- osp_create_instances.yml
- osp_create_multi_instances.yml
- osp_create_network.yml
- osp_create_security.yml 
- osp_flavor.yml
