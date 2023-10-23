Microsoft Azure Presentation and Tutorial

Microsoft Azure Tutorial

Requirements
•	Azure Account (You may want to create Account during

•	.NET 7.0 (You may want to download this from a Web Browser)

•	Visual Studio Code

•	Azure Tools Extension

**Step 1: Creating Your ASP.NET Web App**

Open Visual Studio Code and Create a Folder.

At the Top of the Screen, next to Run, click on Terminal and then click on ‘New Terminal’.

Type: ‘dotnet new webapp --framework net7.0’

Once the Setup is complete, look for the Folder you created on the lefthand side of the screen and expand it by clicking on the arrow, and check that your Project Subfolders and Files have been created, if so, well done! If not, you may want to double check that you have installed .NET 7.0.

Type: ‘dotnet run’

Look for where the URL for your Web App is inside the Terminal, it should look like: ‘http://localhost:5242’, press ‘Ctrl’ and click on the URL or Copy and Paste the URL into the Search Bar of your Browser to see your Web App.

**Step 2: Publishing Your Web App**

At the Top of the Screen, click on ‘View’ and then click on ‘Command Palette’

Search for ‘Azure App Service: Create New Web App (Advanced)’

Sign into your Azure Account if you have one or create an Account instead. All you need to create or sign into your Azure Account is a Microsoft Account (you may want to use your University Email).

Click on ‘Start’ on the Microsoft Azure Homepage and sign up for a free 12 Month Trial. If you have selected ‘Subscription’ in Visual Studio Code before this step, open the Command Palette and search for ‘Azure App Service: Sign Out’, and then sign up for a Subscription before signing in again.

Type in the name of your Web App, for the purpose of this Tutorial ‘Azure-Tutorial’ is sufficient.

Create a new Resource Group, for the purpose of this Tutorial the name ‘Azure-Tutorial-Resource-Group’ is sufficient.

Select your version of .NET, if you installed .NET 7 for this Tutorial, use .NET 7 (STS)

Select your Operating System

Select the closest location
Create a new App Service Plan, for the purpose of this Tutorial, the name ‘Azure-Tutorial-Service-Plan’ will be fine.

Select a Pricing Tier, for the purpose of this Tutorial, Free will suit our purposes nicely.

When asked for an Application Insights resource, click ‘Skip for now’.

When you see the popup ‘Always deploy…’, select Yes.

When the next popup appears, select ‘Deploy’

Once the Web App has been deployed, click ‘Browse Website’ to see if the Web App is working.

**Step 3: Customising Your Web App**

So, now you’ve got a Web App. But it’s empty!

You may want to stop the Web App by pressing any Key inside the Terminal.

To run the Web App go to the Command Palette and type: ‘Azure App Service: Deploy to Web App’ and select your Web App (referred to as a Resource Group). When prompted, simply click ‘Deploy’, and that’s it. Click ‘Browse Website’ at the bottom right of the Screen to visit your Web App.

Open the Subfolder ‘Pages’

Open Index.cshtml

Inside the Div ‘<div class=”text-center”>, type in <p>Hello World!</p>  type:

<p><b>Bold Text</b></p>
<p><i>Italic Text</i></p>
<p><small>Small Text</small><p>

Go to Youtube and find a Video of your liking, for the purpose of this Tutorial you may want to use: https://www.youtube.com/watch?v=y-sBp4MD3is. Open the Video and right click on it and select ‘Copy Embed Code’. In Visual Studio Code simply paste the Embed Code inside the Div.

**Step 4: Cleaning Up**

Open the Microsoft Azure Homepage and click on ‘App Services’ and select the Web App that you created, and click ‘Delete’ at the righthand side of the options at the top of the screen, and then type ‘delete’ in the box at the bottom right of the screen. Click ‘Delete’ and delete the Web App.

Return to the Homepage and click ‘Resource groups’ and select the Resource Group that you created during the Tutorial. Click ‘Delete resource group’ and enter the name of the Resource Group at the bottom righthand side of the Screen to delete the Resource Group.
