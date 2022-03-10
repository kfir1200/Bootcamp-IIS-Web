# ASP.NET Core Web App Project

This project is Visual Studio's ASP.NET Web Core App  template


**Requirements:**

* [Visual Studio with ASP.NET Web Core App](https://visualstudio.microsoft.com/downloads/)
* IIS
* [ASP.NET Core Module](https://dotnet.microsoft.com/permalink/dotnetcore-current-windows-runtime-bundle-installer).


## How to run this project

1. Clone or download source files.
2. Open `Bootcamp.sln` file with visual studio.
3. Build the solution with visual studio.
4. In visual studio right click on the project then choose Publish:

      ![Publish](https://user-images.githubusercontent.com/31624835/157645667-7f92f556-97ee-43c3-b619-6b2146308155.png)

5. Create a new folder in `C:\inetpub\wwwroot` with your site name.
6.  Copy the files from your project publish directoy to the folder yo've created in step 5.

7. open IIS, right click on "Sites" and then choose "Add Website":

      ![IIS](https://user-images.githubusercontent.com/31624835/157647552-3a3d51b1-3b2c-46b0-9685-b1fb8dac8136.png)
     
8. Enter Site name, choose Application pool

9. In "Physical path" choose the folder you created on step 6, for exmaple:

      ![Create_New_site](https://user-images.githubusercontent.com/31624835/157650033-0d98407e-767b-4a53-bf7d-a4ff9a85b598.png)

10. Choose port and then click OK

11. On IIS click on "Start" in the "Managr Website" and then browse to your website:

      ![Start_Website](https://user-images.githubusercontent.com/31624835/157652620-69f8a393-5cfa-4201-a6ee-6d73208d68e8.png)







