# Edge Device Initialization 

## Install ROS2 Humble with ansible playbook
This repository contains an Ansible playbook to install ROS2 Humble on edge devices running Ubuntu 22.04.

1. Clone this repository:
```bash
git clone https://github.com/all4dich/edge_device_init.git
cd edge_device_init
```

2. Run the Ansible playbook:
```bash
ansible-galaxy collection install . --force
ansible-playbook deepx_v3.init_dev.run -i hosts -k -K
```
