# DigitalOcean Reference Architecture Diagrams

This repository hosts a collection of architectural diagrams that I have created in my role as a Solutions Architect at DigitalOcean. These diagrams have served — and continue to serve — multiple purposes:
- To visually explain the workings of DigitalOcean services to the customers I assist.
- To provide a resource for my peers, who may find these diagrams useful in their own work.
- To facilitate my learning of DigitalOcean's services when I joined the company.

I believe that visual representation simplifies learning and helps reinforce understanding. Therefore, I am sharing these diagrams publicly for anyone seeking to understand how DigitalOcean services function.

The architectural diagram presented on this page offers a high-level overview of DigitalOcean's services. For more detailed diagrams of specific services, please visit the subsequent pages.
1. [Droplets](1%20droplets/readme.md)
2. [Managed Kubernetes](2%20kubernetes/readme.md)
3. [App Platform](3%20app%20platform/readme.md)
5. [Managed Databases](5%20dbaas/readme.md)
6. [Managed Load Balancers](6%20lbaas/readme.md)
7. [API](7%20api/readme.md)

**Disclaimer:** These diagrams have not been reviewed by the DigitalOcean product teams for accuracy and may contain errors. They represent my understanding of the services based on research and experience. For official documentation, please refer to [docs.digitalocean.com](https://docs.digitalocean.com).

![DigitalOcean Services Overview](https://lucid.app/publicSegments/view/51b93be1-e8ef-4559-bc66-33ff48ad1f99/image.png)

DigitalOcean offers four deployment options for applications:
1. **Droplets.** Customers fully manage both the operating system and the application.
2. **Managed Kubernetes.** Customers share cluster management responsibilities with DigitalOcean and fully control the applications.
3. **App Platform.** Customers supply the application code or container image for a container environment managed by DigitalOcean.
4. **Functions.** Customers provide function code, and DigitalOcean handles the entire serverless environment, including scaling.

![DigitalOcean Shared Responsibility Model](https://lucid.app/publicSegments/view/9e00f042-7416-4a75-acf1-65fb3e183dd8/image.png)

## Contact
Vasily Prokopov, Solutions Architect at DigitalOcean – [vprokopov@digitalocean.com](mailto:vprokopov@digitalocean.com)  

To learn more about DigitalOcean's services, you are welcome to reach out to sales at [sales@digitalocean.com](mailto:sales@digitalocean.com). A global team of talented engineers will be happy to assist.
