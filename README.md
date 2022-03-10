# ASP.NET Core Web App Project

This project is a Visual Studio ASP.NET Web Core App template that Creates a website on your Microsoft machine and then run the website locally using IIS.

**Requirements:**

* [Visual Studio with ASP.NET Web Core App](https://visualstudio.microsoft.com/downloads/)
* IIS
* [ASP.NET Core Module](https://dotnet.microsoft.com/permalink/dotnetcore-current-windows-runtime-bundle-installer)


## How to run this project

1. Clone or download source files.
2. Open `Bootcamp.sln` file with visual studio.
3. Choose "Release" from the "Configuration Manager" Pane:

      ![Release](https://user-images.githubusercontent.com/31624835/157660130-b04cabbf-ae97-48f0-8dab-45382b5b7393.png)

4. Build the solution with visual studio.
5. In visual studio right click on the project then choose Publish:

      ![Publish](https://user-images.githubusercontent.com/31624835/157645667-7f92f556-97ee-43c3-b619-6b2146308155.png)
      
6. Choose Publish to folder: 

      ![Publish_to_folder](https://user-images.githubusercontent.com/31624835/157659738-e83a62f5-5c29-480e-ad48-f0cdd2d042fe.png)


7. Create a new folder in `C:\inetpub\wwwroot` with your site name.
8.  Copy the files from your project publish directoy, `yourprojectdir\bin\Release\net6.0\publish` to the folder you've created in step 5.

9. open IIS, right click on "Sites" and then choose "Add Website":

      ![IIS](https://user-images.githubusercontent.com/31624835/157647552-3a3d51b1-3b2c-46b0-9685-b1fb8dac8136.png)
     
10. Enter Site name, choose Application pool

11. In "Physical path" choose the folder you created on step 7, for exmaple:

      ![Create_New_site](https://user-images.githubusercontent.com/31624835/157650033-0d98407e-767b-4a53-bf7d-a4ff9a85b598.png)

12. Choose port and then click OK

13. On IIS click on "Start" in the "Managr Website" and then browse to your website:

      ![Start_Website](https://user-images.githubusercontent.com/31624835/157652620-69f8a393-5cfa-4201-a6ee-6d73208d68e8.png)
