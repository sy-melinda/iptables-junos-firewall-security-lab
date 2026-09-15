# Linux iptables and Junos Firewall Security Lab

## Overview

This project documents a controlled university cybersecurity lab focused on host-based firewall configuration, network access control and firewall user authentication.

The first part uses Linux `iptables` to apply default-deny policies, permit selected services , control ICMP and SSH traffic, inspect active rules and remove an existing rule. The second part uses Juniper Junos to configure an access profile, pass-through authentication, a login banner and a security policy requiring firewall authentication.

The purpose of the lab was to understand how firewalls enforce least-privilege access and how authentication can protect network resources from unauthorized users.

> **Ethical Scope:** All configurations and connection tests were performed in an isolated and authorized university lab environment. Credentials and infrastructure details shown in this repository have beeen redacted where appropriate.

## Lab Objectives

- Examine the initial Linux firewall ruleset.
- Configure default `DROP` policies using `iptables`.
- Permit selected HTTP and HTTPS traffic.
- Control ICMP connectivity between designated systems.
- Restrict unauthorized traffic from the attacker virtual machine.
- Permit and test an authorized SSH connection.
- Display numbered firewall rules and delete a selected rule.
- Configure a Junos firewall access profile.
- Associate the profile with pass-through authentication.
- Configure a successful-login banner.
- Apply firewall authentication through a security policy.
- Verify that the intended security controls were active.

## Tools and Environment 

- Linux virtual machines
- VMware
- Linux `iptables`
- ICMP utilities
- SSH
- Juniper Junos
- Juniper SRX firewall
- Command-line interface
