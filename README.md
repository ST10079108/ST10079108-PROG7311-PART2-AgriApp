# AgriApp

Instructions:

1. Download the zipped project from github and open the project from Visual Studio.
2. Check Nuget packages for Microsoft.aspnetcore.identity.entityframeworkcore, Microsoft.EntityFrameworkCore, Microsoft.EntityFrameworkCore.SqlServer, and Microsoft.EntityFrameworkCore.Tools
3. Delete Migrations folder.
4. Click tools, Nuget package manager, Package manager console.
5. run Add-Migrations "Migration-1"
6. run Update-Database
10. run the application
  If for some reason the application won’t run, please try using http instead of https.

  The login details for the preloaded Farmer Profiles:
  Mike
    Email - Mike@mail.com
    Password - Mike1234@

  John
    Email - John@mail.com
    Password - John1234@

  The login details for the preloaded Employee Profile:
  Yui
    Email - Yui@mail.com
    Password - Yui1234@
    
Make sure to Logout before closing the app and reopening it again

System Functionality and user roles:

Upon entering the web app, the user is welcomed by the home page. In the navbar are links to the different pages that are available for users that are not signed in. In the navbar is also a login button which navigates the user to the login page where the user can enter their details. These details have been preloaded. Only the preloaded user accounts can be used when using the app for the first time. After entering the user details, the user will now have access to more navbar links depending on the kind of user they signed in as. They can either sign in as a farmer or an employee. 

If farmer, the user can click on Add Products in the navbar which will take them to the add products page, from there they can fill out a form which prompts them for product information, they can then click Save and the product will be added, the user will be navigated to the My Products page where all their products are listed.

If Employee, the user will now have access to the Add Farmers page and Farmers page. The add farmers page allows the employee to fill out a form that prompts them for farmers details, then they press register and the farmer is registered, they are then taken to the Farmers page. From the farmers page the employee can see a list of all registered farmers, if they click on the products button next to a farmer, they will see all the products that the specific farmer has added.
