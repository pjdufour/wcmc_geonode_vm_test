# wcmc_geonode_vm_test

This repo is used to launch a UNEP WCMC GeoNode into a Vagrant Virutal Machine for testing.

## Usage

To launch the test VM do the following

```shell
ansible-galaxy install GeoNode.geonode
vagrant up
```

## Defaults

As described in `ansible.cfg`, the roles path is hardcoded to `~/.ansible/roles`.  Roles from Ansible Galaxy will be downloaded there.  The playbook only uses the one `GeoNode.geonode` role.

If you want to change the repository or branch used, you can adjust the `vars` in `playbook.yml`.
