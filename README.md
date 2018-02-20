# Cloud Formation Script for MapR 6.0+MEP 4.1 and MapR Data Science Refinery

This uses an [AWS Cloud Formation](https://aws.amazon.com/cloudformation/) script to prompt the user to create a MapR cluster of some number of nodes with MEP 4.1 and then select some number of [MapR Data Science Refinery](https://mapr.com/products/data-science-refinery/) containers to spin up alongside this cluster (same subnet/VPC) that will be pre-configured with the capability to submit jobs to this cluster.

Base script is pulled from [mapr/mapr-cloud-templates](https://github.com/mapr/mapr-cloud-templates) and this is the full script that includes the ability to spin up an openvpn server 
