# Zabbix template for Microsoft Windows Server

Features:
  Performance counters.
  CPU Low Level Discovery.
  Mounted file system Low Level Discovery.

Difference from default Windows OS template:
  CPU's discovery and triggers per CPU's.
  Mounted file system discovery and triggers per logical disk.
  More items and triggers prototypes for Mounted file system discovery.
  Triggers are oriented for Microsoft Windows Server running Microsoft SQL Server.

Missing:
  Network interface items.
  
Supported versions:
Tested on Microsoft Windows Server 2012, 2012 R2 and 2016. It may work with earlier versions, but some items (with missing performance counters) may be unsupported.

Tested on Zabbix 3.4.0. It may work with earlier versions, but some items (for example service.info[service,<param>]) may be unsupported.
