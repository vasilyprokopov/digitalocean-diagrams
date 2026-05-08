[back](../README.md)
![DigitalOcean Regional Load Balancers](https://lucid.app/publicSegments/view/b9909df9-ffc5-407b-b38e-048cc4a31964/image.png)

Quick facts:
- The Regional Load Balancer is a Layer 4 service.
- You can add a firewall to the Regional Load Balancer to deny or allow specific IP addresses or ranges ![API](https://img.shields.io/badge/-API%20Only-blue)
- The Regional Load Balancer, by default, exposes a public IP address, making it an external load balancer.  
- It can also be configured to expose only a private IP address, making it an internal load balancer for use within a VPC.
- Droplets can be dynamically attached to or detached from the Managed Load Balancer using tags.
- You can only have a single TLS certificate per rule and port.

![DigitalOcean Global Load Balancers](https://lucid.app/publicSegments/view/8d72bfeb-4be1-4937-9f23-0d6a40f99eaa/image.png)
