# Clean up

In the [previous step](./CheckTheEmotion.md) you built out the game to capture frames from the camera and look for emotions. In this step you will clean up your Azure resources.

## Deleting the resource group

Everything you created for this workshop should have been in the same resource group. This resource group was created when you first deployed the Azure App Service, and was used when you created the Face API.

Deleting this resource group will delete all the resources created.

1. Open the Azure Portal from [portal.azure.com](https://portal.azure.com/?WT.mc_id=hackwithazure-hackathon-cxa). Log in if required.

1. From the search bar at the top, search for the resource group that was created. Select it from the results.
  
   ![Searching for the resource group in Azure](../images/SearchForResourceGroup.png)

1. Select **Delete resource group**.
  
   ![The delete resource group button](../images/DeleteResourceGroupButton.png)

1. The confirmation panel will appear showing all the resources that will be deleted along with the resource group.

   ![The delete resource group confirmation](../images/DeleteResourceGroupConfirm.png)

1. Enter the name of the resource group and select *Delete*.

All the resources in this group will be deleted.
