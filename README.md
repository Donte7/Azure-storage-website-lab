# Azure-storage-website
👀 Watch me build this lab here!

Create a storage website with Microsoft Azure

## 🖥️ Azure Static Website Setup Guide
This guide walks you through creating and hosting a static website on Azure Storage.

1️⃣ Create a Storage Account

1.Log in to the Azure Portal

2.Click Create a resource

3.<img width="3358" height="1682" alt="image" src="https://github.com/user-attachments/assets/4cbbf802-636f-4f56-88cd-371f13f8bc7e" />


4. Select Storage account

5. Choose your subscription and resource group

6. Enter a unique storage account name

7. Select a region

8. Leave default settings

9. Click Review + Create, then Create


2️⃣ Enable Static Website Hosting

1. Open your storage account
2. Select Static website from the left menu
3. Toggle Enabled
4. <img width="3360" height="1680" alt="image" src="https://github.com/user-attachments/assets/b798fbcc-b983-443e-978d-31f54e36f2ea" />

5. Set the following:

* 🏠 Index document name: index.html
* ⚠️ Error document path (optional): 404.html
* <img width="3356" height="1680" alt="image" src="https://github.com/user-attachments/assets/71acb4d7-dd6e-49d4-82e3-6f13f497ad57" />


6. Click Save changes
7. Copy the Primary endpoint URL — this will be your live website URL

3️⃣ Create the Website File

1. Create a file named index.html
2. Add your HTML content
3. Save the file
4. 
4️⃣ Upload Files to Azure

1. Open Containers

2. Select the $web container

3. Upload your index.html file
4. <img width="3356" height="1680" alt="image" src="https://github.com/user-attachments/assets/97281956-2b9c-40fa-94c9-cf3dbae172bd" />

5. Confirm the upload

5️⃣ View the Live Website 🌍

1. Go back to Static website
2. Open the Primary endpoint URL
3. Your website should now be live!









