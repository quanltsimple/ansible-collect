# Prometheus, Grafana, Node Exporter, AlertManager, Blackbox Exporter Setup using Ansible for Linux

In this project, we are configurating prometheus with blackbox_exporter, alertmanager on one instance and node_exporter, grafana on another instance using ansible.

## Getting Started

Step 1: Update ip address of both instances in inventory, /roles/prometheus/templates/prometheus.conf.j2 file.

Step 2: Run ansible command to setup prometheus server with node exporter

Ansible command: ansible-playbook playbook.yml
