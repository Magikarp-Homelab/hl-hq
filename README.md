# Homelab HQ
Homelab HQ Repo, Overview & Organizing

## Hardware

Home Router -> Random Switch -> Firewall -> Lab

Firewall
Zyxel vpn2s

Storage Server aka Old PC aka Jotunheim
* CPU: i5 4460, 3.2GHz 4 Core
* MoBo: Gigabyte GA-H97-HD3
	* Chipset H97
	* Socket LGA 1150
	* RAM 4x DDR3 1333/1600 max 32GB
* GPU: (R9 390 Nitro Tri-X Sapphire)
* RAM: 2x 4GB, 1600MHz, DDR3, Crucial Ballistix sport XT
* PSU: 620W Seasonic Bronze
* Storage
	* WD Black 1TB
	* WD Black 1TB
	* WD Black 1TB
	* WD Blue 1TB
	* WD Blue 2TB -> Backup/FileStorage
	* Sata SSD 250GB
	* TOTAL: 6TB + OS ssd

Application Server aka NK v5.0 aka Nidavellir
* CPU: AMD Ryzen 5 4500, 3.6GHz 6 Core
* MoBo: AsRock B550M Pro4
  * Chipset AMD B550
	* Socket AM4
	* RAM 4x DDR4 3200 max 128GB
* GPU: -
* RAM: 4x 32GB 3200MHz, DDR4
* PSU: 750" Gold Fractal Ion

Monitoring/Dashboard/Wiki aka Niflheim
* Raspberry Pi 3B

## Planned Techstack Dump
VMHOST
* Proxmox

Niflheim
* Bookstack
* Prometheus
* Grafana

Jotunheim
* MySQL
* MongoDB
* Apache Hadoop
* Apache Pulsar
* Cloud ?
* Plex/Jellyfin ?
* Random Storage ?

Nidavellir
* Apache Zookeeper
* Apache Spark
* Apache Druid ?
* Apache Superset
* Random Batches
* Random Crawlers
* Hosting Gameservers

## Current Diagram
Planned not yet built
<img src="https://github.com/Magikarp-Homelab/hl-hq/blob/main/network_diagram.png"/>

## Naming Concept
Physical Servers are namen after the 9 reals from norse mythology because pog.

* Asgard (Gods)
* Alfheim (Light Elves)
* Nidavellir (Dwarves/Dark Elves) [Taken by application server]
* Midgard (Earth)
* Jotunheim (Giants) [Taken by storage server]
* Vanaheim (the other Gods)
* Niflheim (Primordial Ice) [Taken by raspberry]
* Muspelheim (Primordial Fire)
* Helheim (Hell)


VMs & Pods will be named after entities in those realms.
