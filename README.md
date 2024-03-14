# Ansible Playbooks using juniper.device 

[**About juniper-device-ansible-modules-examples**](README.md#about-juniper-device-ansible-modules-examples)  
[**Juniper hardware and the example playbooks**](README.md#juniper-hardware-and-the-example-playbooks)  
[**Getting started with Ansible and Junos**](README.md#getting-started-with-ansible-and-junos) 

# About juniper-device-ansible-playbooks

This project contains Ansible playbooks that may be used to interact with devices running Junos OS and Junos Evolved. This repository uses Ansible Base and Juniper's Ansible Collection for Junos ([juniper.device](https://galaxy.ansible.com/ui/repo/published/juniper/device/)). 

The modules labeled 1XX are considered building block modules that have been provided by Juniper contributors. All other modules are provided by the extended Juniper Automation Community. 

If you are looking for the older examples using Ansible Core, please check out these repositories:
 - [juniper_junos_ansible_modules_examples](https://github.com/JNPRAutomate/juniper_junos_ansible_modules_examples)
 - [junos-automation-with-ansible](https://github.com/JNPRAutomate/junos-automation-with-ansible)
 - [ansible-junos-examples](https://github.com/JNPRAutomate/ansible-junos-examples)
 
# Juniper hardware and the example playbooks

 This repository is to be used with devices running Junos OS or Junos Evolved.  Example of hardware platforms include, but are not limited to, the MX, PTX, ACX, QFX, EX, and SRX. Example playbooks will be using the juniper.device modules listed below:

- command — Execute one or more CLI commands on a Junos device.
- config — Manipulate the configuration of a Junos device.
  - Edit, load, commit, save, rollback, or retrive the config
- facts — Retrieve facts from a Junos device.
- jsnapy — Execute JSNAPy tests on a Junos device.
- ping — Execute ping from a Junos device.
- pmtud — Perform path MTU discovery from a Junos device to a destination.
- rpc — Execute one or more NETCONF RPCs on a Junos device.
- software — Install software on a Junos device.
- srx_cluster — Enable or disable an SRX chassis cluster configuration.
- system — Initiate operational actions on the Junos system.
  - Actions include reboot, shutdown, halt, and zeroize
- table — Retrieve data from a Junos device using a PyEZ table/view.

# Getting started with Ansible and Junos

Start at the [Ansible for Junos documentation page](https://www.juniper.net/documentation/product/us/en/ansible-for-junos-os/) to evaluate, install or use Ansible for Junos to easily manage and configure devices running Junos in your network. One will find the Release Notes, Get Started, Developer Guides, Day One Books, Support Resources, and Configuration Examples and Guides. 
