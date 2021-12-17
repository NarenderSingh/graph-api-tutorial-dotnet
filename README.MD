# Build ASP.NET Core MVC apps with Microsoft Graph

This tutorial teaches you how to build an ASP.NET Core web app that uses the Microsoft Graph API to retrieve calendar information for a user.

## Prerequisites
Before you start this tutorial, you should have the .NET Core SDK installed on your development machine. If you do not have the SDK, visit the previous link for download options.

You should also have either a personal Microsoft account with a mailbox on Outlook.com, or a Microsoft work or school account. If you don't have a Microsoft account, there are a couple of options to get a free account:

You can sign up for a new personal Microsoft account.
You can sign up for the Office 365 Developer Program to get a free Office 365 subscription.

## Note
This tutorial was written with .NET Core SDK version 5.0.102. The steps in this guide may work with other versions, but that has not been tested.

### Please refer the below documentation
(https://docs.microsoft.com/en-us/graph/tutorials/aspnet-core)


## Add Azure AD authentication
dotnet user-secrets init<br>
dotnet user-secrets set "AzureAd:ClientId" "YOUR_APP_ID"<br>
dotnet user-secrets set "AzureAd:ClientSecret" "YOUR_APP_SECRET"<br>