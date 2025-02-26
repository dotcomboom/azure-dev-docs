---
title: Deploy the static Node.js app files to Azure Storage from Visual Studio Code
description: Tutorial part 4, deploy the files to Azure Storage
services: app-service
author: kraigb
manager: barbkess
ms.service: app-service
ms.topic: conceptual
ms.date: 09/24/2019
ms.author: kraigb
---

# Deploy the website to Azure Storage

[Previous step: Create a Storage account](tutorial-vscode-static-website-node-03.md)

In this step, you use Visual Studio Code to deploy the static website files created in the previous steps to Azure Storage, which then hosts and serves those files.

1. In Visual Studio Code, go to the **Azure Storage** explorer, expand your subscription, expand the node for the Azure Storage account that you created in the previous step, then expand the **Blob Containers** node. The `$web` container is where you deploy your app code.

    ![Azure Storage nodes in the Azure Storage explorer](media/static-website/storage-nodes.png)

1. Select the **Files** explorer, right-click on your *build* folder, and choose **Deploy to Static Website**:

    ![Deploy to Static Website command](media/static-website/deploy-build.png)

1. When prompted, choose the Storage account that you created previously.

1. When deployment is complete, a message appears with a **Browse to website** button. Select that button to open the primary endpoint of the deployed app code.

    ![Deployment complete message](media/static-website/deployment-complete.png)

    ![Static website running in Azure](media/static-website/azure-app.png)

> [!div class="nextstepaction"]
> [My site is on Azure](tutorial-vscode-static-website-node-05.md) [I ran into an issue](https://www.research.net/r/PWZWZ52?tutorial=node-deployment-staticwebsite&step=create-storage)
