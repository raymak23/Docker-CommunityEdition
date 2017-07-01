# Docker-CommunityEdition
  This project is written in Visual studio 2017 using Microsoft ARM template. 
  
# Prerequisite
  * Visual studio 2017
  * Powershell 5
  * Windows 7 or higher
  * Azure subscription
  
# Technologies / Features
  * Docker Community Edition (CE) for manager node hosted in OpenLogic CentOS Linux VM.
  * Microsoft Windows Active directory with Windows Server core 2016 VM.
  * Build server with Windows Server 2016 VM for building images for applications that will be containerized.
  * Worker nodes with attributes "Wrk" in Windows server core 2016 VM that will be hosting containers.
  * Internal Azure Load balancer for high availability.
  

# Upcoming features:
  * Install Active directory after Azure virtual machine is deployed.
  * Install Docker CE on manager node after Azure virtual machine is deployed.
  * Install Docker for windows on all worker and build nodes after Azure virtual machine is deployed.
  * Join all windows VM in domain.
  * Create swarm cluster on manager node.
  * Join swarm cluster on worker nodes.
    
