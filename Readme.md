# Getting Started

## Prerequisites

To use the Microsoft Graph Connect Sample for Node.js, you need either a [Microsoft account](https://www.outlook.com/) or a [work or school account](http://dev.office.com/devprogram)

## Register the application

1. Sign into the [App Registration Portal](https://apps.dev.microsoft.com/) using either your personal or work or school account.

2. Choose **Add an app**.

3. Enter a name for the app, and choose **Create application**. 
	
   The registration page displays, listing the properties of your app.

4. Copy the Application Id. This is the unique identifier for your app. 

5. Under **Application Secrets**, choose **Generate New Password**. Copy the password from the **New password generated** dialog.

   You'll use the application ID and password (secret) to configure the sample app in the next section. 

6. Under **Platforms**, choose **Add Platform**.

7. Choose **Web**.

## Configure and run the sample

1. Add values for **client_id** and **client_secret** in the `.env` file in your Glitch project, using the application ID and password that you copied during app registration.

Now you can try out the app.

2. Choose the **Connect** button.

3. Sign in with your personal or work or school account and grant the requested permissions.

4. Optionally edit the recipient's email address, and then choose the **Send mail** button. When the mail is sent, a Success message is displayed below the button.

> Note: To understand the code for calling the Microsoft Graph API in a Node.js app, see [Get started with Microsoft Graph in a Node.js app](https://graph.microsoft.io/en-us/docs/platform/nodejs).
