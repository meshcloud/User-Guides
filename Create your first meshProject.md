# Creation of a meshProject

`Customization hints:
In order to make the guide nicer for the users replace the general screenshot with a screenshot from your production environment to match the colours and options they see in the meshPanel while following the guide. Make sure that the tags required and used during the creation are explained either in this guide or in the description field in the meshPanel. Furthermore please consider any naming schemas for the name and identifier for a project.`

If you are not familiar with what a meshProject is, please check the [official meshcloud documentation](https://docs.meshcloud.io/docs/meshcloud.index.html).

## Pre-Requisits

- Permissions: Your user needs either the Customer Admin or Customer Owner role in the meshCustomer you want to create the meshProject in
- Valid Payment Method: meaning the payment method is not expired and assigned to your customer

## :shoe: Step to Step Guide

 1. Make sure you are in the meshCustomer the new meshProject will belong to. Do this by checking the drop-down in the upper-left corner.
![Select meshCustomer in the upper left corner](https://github.com/meshcloud/User-Guides/blob/b8e2b6e183c82c86bc3e1b14173d267f5652281c/assets/PickCustomer.png "Pick meshCustomer")
 2. Start the meshProject creation wizard by clicking the "+ Create" -Button on the meshCustomer dashboard.
 ![Start meshProject Creation Wizard](https://github.com/meshcloud/User-Guides/blob/b8e2b6e183c82c86bc3e1b14173d267f5652281c/assets/StartWizard.png "Start Wizard")
 3. First you have to give your project a name. The best practice is to use the name of the application, product, or project plus the environment type. The identifier is automatically generated but can be modified by you. We recommend to keep the identifier as it is. ![General Information](https://github.com/meshcloud/User-Guides/blob/b8e2b6e183c82c86bc3e1b14173d267f5652281c/assets/PickaName.png "Naming")
 4. The lower part of the first page provides you the possibility to tag your meshProject. Some tags are required to be specified by you. You can recognize the required tags by the red line on the left side of the input field. Some of the tags you chose might have an impact on the landing zone you are allowed to chose if a policy exists that might restricts the usage. Click next:arrow_right:![Tags](https://github.com/meshcloud/User-Guides/blob/b8e2b6e183c82c86bc3e1b14173d267f5652281c/assets/Tags.png "Various Tags")
 5. Select the payment method provided via the meshCustomer. Click next:arrow_right:
 6. Now we come to the most important part. Choose at least one of the platforms for your future meshProject. The marketplace with interesting services provided by your organization is selected by default. If you want to have for example an AWS account pick AWS and select a provided meshLZ as well. Click next :arrow_right: ![Platform](https://github.com/meshcloud/User-Guides/blob/b8e2b6e183c82c86bc3e1b14173d267f5652281c/assets/PlatformAndLZ.png "Platform and Landing Zone")
 7. Now add any team members who should have access to the new meshProject and the corresponding cloud tenants. You can also add yourself by clicking the "Add myself" button. Don't forget to confirm your action by clicking the "+" and selecting a role. ![Add Users and Groups](https://github.com/meshcloud/User-Guides/blob/cfbe2ccfd4fefed40e1468db2fc51e1ecda83cc9/assets/AddUsers.png "Add Users and Groups")
 8. Finally! The moment has come and you can create your project. Click the "Create Project" button to confirm your new project. It will take a while to create the project and add the users to the tenants. Check the replication status of the new OpenShift Tenant. After a while it should look like this... ![Check Replication Status](https://github.com/meshcloud/User-Guides/blob/b8e2b6e183c82c86bc3e1b14173d267f5652281c/assets/ReplicationStatus.png "Add Users and Groups")

### Congratulations you are done :tada:
