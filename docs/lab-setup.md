# Cybersecurity Lab Setup

## Overview

This project is a controlled cybersecurity laboratory designed for practicing Linux administration, networking, security monitoring, and defensive security techniques.

The environment uses virtual machines to separate security testing from the primary computer.

## Virtual Machines

### Kali Linux

Purpose:

* Security testing
* Network reconnaissance
* Vulnerability assessment
* Security tooling

### Linux Server

Purpose:

* Server administration
* SSH
* Firewall configuration
* Logging
* Defensive security

### Target VM

Purpose:

* Controlled target for security testing
* Testing firewall and monitoring configurations
* Practicing vulnerability assessment in an authorized environment

## Defensive Security

The laboratory includes defensive technologies such as:

* UFW
* Suricata
* System logging
* Security alerts
* Network monitoring

## Network Design

The long-term goal is to operate the virtual machines on a private, isolated laboratory network.

```text
                Private Lab Network
                       │
                   [Router]
                       │
          ┌────────────┼────────────┐
          │            │            │
       [Kali]       [Server]     [Target]
       Testing      Defensive     Target
```

## Project Status

The laboratory is currently under development.

Future work includes:

* Private physical network
* Network segmentation
* Centralized logging
* Additional monitoring
* Vulnerability assessment
* Security automation
* Documentation and testing
