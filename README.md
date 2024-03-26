# Ansible System Information Playbook

This repository contains an Ansible playbook for gathering and displaying system information about your remote hosts. The playbook will print out the Linux distribution release, processor type, and the amount of free memory in megabytes for each targeted host.

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes.

### Prerequisites

What things you need to install the software and how to install them:

- Ansible installed on your control node (the machine that will run the playbook).
- Access to one or more remote hosts, with Ansible configured to manage them (SSH access and a user with sufficient privileges).

### Installing

1. Clone this repository to your control node:

```bash
git clone https://github.com/kejian-tong/Ansible_training.git

cd yourproject

```bash

Ensure your Ansible inventory file (/etc/ansible/hosts by default, or another file specified by -i when running ansible-playbook) is up to date with the hosts you intend to target.

Usage

Run the playbook using the following command:

```bash
ansible-playbook playbook.yml

```bash

Replace playbook.yml with the path to the playbook file if you have stored it in a different location or named it differently.

Playbook Details
Hosts targeted: All hosts in your Ansible inventory by default. Modify the hosts parameter in the playbook to target a specific group or host.
Gathered facts:
Linux distribution release
Processor type
Free memory in megabytes
Contributing
Please read CONTRIBUTING.md for details on our code of conduct, and the process for submitting pull requests to us.

Versioning
We use SemVer for versioning. For the versions available, see the tags on this repository.

Authors
Your Name - Initial work - kejian-tong

License
This project is licensed under the MIT License
