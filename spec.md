## Boise State R2 Compute Cluster

### Specifications

#### Operating System
- CentOS 7

#### Head Nodes – High Availability Fail Over:
- Mother Board: Dell PE R730/xd
- CPU: Dual Intel Xeon E5-2623 4 core 2.6GHz
- Memory: 64GB
- EtherNet: Dual 10GigE, Dual GigE
- InfiniBand: Mellanox ConnectX-3 VPI FDR, QSFP+ 40/56GbE

#### CPU Nodes
- Mother Board: Dell PE R630
- CPU: Dual intel Xeon E5-2680 v4 14 core 2.4GHz
- Memory: 192GB
- EtherNet: Quad Port GigE
- InfiniBand: Mellanox ConnectX-3 VPI FDR, QSFP+ 40/56GbE

#### GPU Nodes
- Mother Board: Dell PE 730/xd
- CPU: Dual Intel Xeon E5-2680 v4 14 core 2.4GHz
- GPU: dual Nvidia Tesla NVLink P100’s (3584 cores each)
- Memory: 256GB
- EtherNet: Quad Port GigE
- InfiniBand: Mellanox ConnectX-3 VPI FDR, QSFP+ 40/56GbE

#### Data Storage
- Dell MD3460 12G SAS [360 TB] Raid-6 XFS

#### File Systems
- Head Nodes 600 G mirrored /cm/shared/apps 5Tb /home 38Tb /scratch 303T
- Compute/GPU Nodes 600G /cm/shared/apps 5Tb /home 38Tb /scratch 303T
