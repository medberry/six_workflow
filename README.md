# Sixth simple Ansible Tower mini-demos

## Workflow

In this sixth example, we'll create a vm in openstack in one playbook.
Then we'll make sure it is ready (either in that playbook or a follow on)
Then we'll add it to the inventory (or trigger an inventory refresh via api)
We will then configure that new VM somehow.
Validate the configuration.
Teardown the VM.
Re-refresh the inventory.

