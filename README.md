By default, FortiSIEM supports Snort IPS: FortiSIEM External Systems Configuration Guide - Snort IPS, but it is possible to use Suricata as an alternative (Suricata being a widely-used open-source intrusion detection system).

Configuring FortiSIEM:

Add a new device by navigating to ADMIN -> Device Support -> Devices/Apps, then select New. Name the entry appropriately (e.g. 'suricata') and set the Version field to Any (log formats generally remain consistent between Suricata versions).

Navigate to ADMIN -> Device Support -> Event Attributes to add new Event attributes to be used when parsing Suricata logs.

As a suggestion, consider adding the Event SID (generally useful for investigating Suricata alerts) and Classification attributes (for dashboard usage and visualization).

Navigate to ADMIN -> Device Support -> Parsers and add a new Parser.
