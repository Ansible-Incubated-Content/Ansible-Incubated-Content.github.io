+++
title = 'Azure Terraform Deployment'
date = 2024-02-26T17:07:48-05:00
draft = true
weight = 4
summary = 'Use Terraform to provision Azure infrastructure, then the Ansible Automation Platform installer to install AAP on the provisioned infrastructure.'
+++

These examples are intended to be modified and updated for individual uses as there is no one-size-fits-all deployment model for Ansible.  The  machine shapes, the database service, and networking configuration will all depend on organizational circumstances.

### Terraform Example

The Terraform example uses CF templates to deploy Azure infrastructure.
