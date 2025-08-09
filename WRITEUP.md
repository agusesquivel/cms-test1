# Write-up Template

### Analyze, choose, and justify the appropriate resource option for deploying the app.

*For **both** a VM or App Service solution for the CMS app:*
- *Analyze costs, scalability, availability, and workflow*
- *Choose the appropriate solution (VM or App Service) for deploying the app*
- *Justify your choice*

### Assess app changes that would change your decision.

*Detail how the app and any other needs would have to change for you to change your decision in the last section.* 

I chose Azure Web App because it’s a PaaS service that lets me deploy and manage the CMS without handling infrastructure, while providing scalability, high availability, built-in security, and easy integration with CI/CD tools.
Managed service.

If I had chosen a Virtual Machine (VM) instead of Azure Web App, I would have full control over the operating system and server configuration, but I would also need to handle updates, security patches, scaling, and monitoring manually. This would take more time and requiere more technical maitenance.


Scalability and availability
It can scale up or out automatically and provides high availability, which is important if the CMS gets traffic spikes

Integration with development tools
It connects easily with GitHub, Azure DevOps, or Bitbucket for continuous deployment, so I can update the CMS quickly with no downtime.

Support for multiple technologies
Azure Web App supports several languages and frameworks, making it flexible for different CMS options.

Built-in security
It offers HTTPS, authentication, and Azure Active Directory integration to protect the app

Cost efficiency
It’s cheaper and simpler than running a VM because I only pay for the plan and resources I use

The choice depends on the application’s requirements, for example, if it needs special system configuration, additional services, or greater control over the environment, a VM might be the better option
