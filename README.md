## QNAP TS-469 Template

__Zabbix 5.0LTS SNMP template for monitoring QNAP TS-469 network storage devices.__

1. Items System
   - CPU Usage
   - Firmware upgrade 
   - Free memory
   - Memory usage
   - System temperature
   - Total memory
2. Volumes (discovery)
   - Item prototypes
     - Free size
     - Total size
     - Used size
     - Usage
   - Trigger prototypes
     - Free space is critically low
     - Free spase is low
     - Volume is full
   - Graph prototypes
     - Volume space
4. Hard disks (discovery)
   - Item prototypes
     - SMART status
     - Temperature
   - Trigger prototypes
     - SMART status isn't good
5. Triggers
   - Firmware upgrade available
   - High CPU utilisation
   - High memory utilisation
6. Graphs
   - Resources Utilisation

