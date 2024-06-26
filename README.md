# Web Application Setup

## Prerequisites

- Vagrant
- VirtualBox
- Ansible

## Setup

1. Clone this repository.
2. Navigate to the repository directory.
3. Run `ansible-galaxy collection install -r requirements.yml` to install the requirements needed to run.
4. Run `vagrant up` to provision the VM and set up the environment.
5. Access the application in your browser at `http://localhost:3000`.

The playbook will set up Docker, clone the application repository, and start the necessary Docker containers for the frontend and backend applications.
