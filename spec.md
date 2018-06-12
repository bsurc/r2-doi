## Boise State R2 Compute Cluster

### Specifications

#### Operating System
- CentOS 7

#### Head Nodes – High Availability Fail Over (2)
- Mother Board: Dell PE R730/xd
- CPU: Dual Intel Xeon E5-2623 4 core 2.6 GHz
- Memory: 64 GB
- EtherNet: Dual 10GigE, Dual GigE
- InfiniBand: Mellanox ConnectX-3 VPI FDR, QSFP+ 40/56GbE

#### CPU Nodes (25)
- Mother Board: Dell PE R630
- CPU: Dual intel Xeon E5-2680 v4 14 core 2.4 GHz
- Memory: 192 GB
- EtherNet: Quad Port GigE
- InfiniBand: Mellanox ConnectX-3 VPI FDR, QSFP+ 40/56GbE

#### GPU Nodes (5)
- Mother Board: Dell PE 730/xd
- CPU: Dual Intel Xeon E5-2680 v4 14 core 2.4 GHz
- GPU: dual Nvidia Tesla NVLink P100’s (3584 cores each)
- Memory: 256 GB
- EtherNet: Quad Port GigE
- InfiniBand: Mellanox ConnectX-3 VPI FDR, QSFP+ 40/56GbE

#### Data Storage
- Dell MD3460 12G SAS [60 TB] Raid-6 XFS
- Dell MD3000 6G SAS [360 TB] Raid-6 XFS

#### File Systems
- Head Nodes 600 GB mirrored /cm/shared/apps 5 TB /home 38 TB /scratch 303 TB
- Compute/GPU Nodes 600 GB /cm/shared/apps 5 TB /home 38 TB /scratch 303 TB
