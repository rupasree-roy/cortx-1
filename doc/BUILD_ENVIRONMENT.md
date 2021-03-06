### BUILD AND TEST ENVIRONMENT FOR CORTX

Building and testing CORTX can be done using a single system.  Obviously CORTX is designed to be a scale-out distributed object storage system but these instructions currently only cover setting up a single node environment.

Currently CORTX requires the CentOS 7.7.1908 distribution running the 3.10.0-1062 kernel. Building it and testing it can be done on either a physical or virtual machine matching these requirements.  We have provided instructions to [install dependencies](InstallingDependencies.md).

For your convenience, we offer a [pre-built VM image (OVA)](https://github.com/Seagate/cortx/releases/tag/VA) which can be used for development and testing. 

A CORTX development environment requires RoCE—RDMA over Converged Ethernet and TCP connectivity.
   - Note: The CORTX stack currently does not work on Intel's OmniPath cards.
