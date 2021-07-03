# Write-up Template

### Analyze, choose, and justify the appropriate resource option for deploying the app.

*For **both** a VM or App Service solution for the CMS app:*
- *Analyze costs, scalability, availability, and workflow*
- *Choose the appropriate solution (VM or App Service) for deploying the app*
- *Justify your choice*

APP SERVICE:
Because the CMS application in python is quite light, the costs, scalability and availability are quite well suited and it does not need a lot of computational resources. Therefore, since the app is a beta or test app, the payment is constant and the price it will have is not very high. Thanks to the CI/CD via github makes the deployment quite easy. 

VM:
The Vm allow for greater customization and their use for deployment is quite reasonably priced. 
So its cost, scalability and availability of a CMS application is a good choice.  
Because VM allow for greater tuning, the developer can adjust and customize the VM to make the CMS application as optimized as possible.

My Choice:
I chose app service for its easy deployment in azure with github, azure devops among others, because it is a lightweight application created with the flask framework and is compatible with app service. 


### Assess app changes that would change your decision.

*Detail how the app and any other needs would have to change for you to change your decision in the last section.* 

APP SERVICE: 
In the case that the CMS application needs more computational power due to some functionality, for example linked to using artificial intelligence for the images you have or playing videos with great duration, this would increase the cost if it is not further optimized and if it needs some update that is not available in the app service, this would be a limitation for which we should think if it is our best option. 


VM:
If the CMS becomes more elapsed and your peaks of visits are too high, it could make it more expensive to pay for the VM usage service. Depending on the rotation of the company with its developers as it would require the developer to know how the VM is customized for optimization and bringing in a new developer would take time to make changes to the app as they should already understand the VM configurations. 
