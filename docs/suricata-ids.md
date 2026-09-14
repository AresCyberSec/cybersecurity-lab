# Suricata Intrusion Detection System

## Overview

Suricata is being used in this laboratory as a network intrusion detection system (IDS) to monitor network traffic and generate security events.

## Configuration

Suricata is configured to monitor the Linux host's wireless network interface.

The system uses:

* Suricata 7.x
* AF_PACKET packet capture
* EVE JSON logging
* Fast alerts
* Network traffic monitoring

## Logging

Suricata generates security events that can be reviewed through its log files.

Important logs include:

* `eve.json`
* `fast.log`
* `stats.log`
* `suricata.log`

## Alerting

A custom alerting service monitors Suricata events and provides desktop notifications when security events are detected.

This allows the system to provide near-real-time awareness of potential network activity.

## Skills Demonstrated

* IDS deployment
* Linux security monitoring
* Network interface configuration
* JSON log analysis
* Linux services
* Security alert automation
* System troubleshooting

## Project Status

**Operational / In Progress**

Suricata is currently running and monitoring network traffic. Additional detection rules, alert analysis, and automated response capabilities will be developed as the laboratory grows.
