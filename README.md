# Call Graph API from a JavaScript Single Page Application (SPA) using Azure Active Directory v2 endpoint via msal.js
==============================================================

| [Getting Started](https://aka.ms/aadv2)| [Code Samples](https://github.com/azure-samples/) | [Support](README.md#community-help-and-support)
| --- | --- | --- |
<!--
## Go [here](https://docs.microsoft.com/azure/active-directory/develop/guidedsetups/active-directory-javascriptspa) for information about this code sample and how to configure it

Commenting out until we release the guided setup in docs

-->

## How to run this solution

> Full instructions coming soon

### Add your application registration information to your solution

1. Go to the [Microsoft Application Registration Portal](https://apps.dev.microsoft.com/portal/register-app) to register an application
2. Enter a name for your application and your email 
3. Make sure the option for *Guided Setup* is unchecked
4.	Click `Add Platform`, then select `Web`
5. Add a redirect URL to your application's registration information. See below for how to obtain the redirect URL in Visual Studio
6. Click *Save*

> #### Visual Studio instructions for obtaining redirect URL using SSL
> In Visual Studio, configure your project to use SSL, and then use the SSL URL to configure your application’s registration information using the instructions below:
> 1.	In Solution Explorer, select the project and look at the `Properties` window (if you don’t see a Properties window, press F4)
> 2.	Copy the value from `SSL URL` to the clipboard
> 3.	Select the `Project` menu and then select `{Project} Properties...` (where {Project} is the name of your project)
> 4.	Open the `Web` tab
> 5.	Paste the value of `SSL URL` in the `Project Url` field
> 6.	Switch back to the Application Registration Portal and paste the value in the `Redirect URL` as redirect URL, then click *Save*


#### Configure your JavaScript SPA application

1. Open `msalconfig.js` file and replace <code>Enter_the_Application_Id_here</code> with the Application Id you just registered 

## Community Help and Support

We use [Stack Overflow](http://stackoverflow.com/questions/tagged/azure-active-directory) with the community to provide support. We highly recommend you ask your questions on Stack Overflow first and browse existing issues to see if someone has asked your question before.

Copyright (c) Microsoft Corporation.  All rights reserved. Licensed under the MIT License (the "License");
