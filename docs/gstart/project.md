## Project
<div style='text-align: justify;'> 
<p>Project it is defined as a collection of files and folders plus the metada on a specific server network shared folder. Project it is the unit of data that users will work in a distrubted and colaborative approach and it encapsulate a network shared folder metada providing all the users with access to that network shared folder a structured and user-friendly view on it from the Ez2Cloud interface. Before any activity the Ez2cloud admin user from your company must create a project that will be the starting point where users can view and label the files and folders. </p>

<p>Only a user with Administrator ou Project Administrator role can add a new project. When doing so, it is mandatory to provide a name, description, an end date. Also the project as it the view from Ez2Cloud to a shared network folder on create the project it is mandatory to define local network path. This is the absolute path to a folder on the company File Server. If need the project must also get user name and password to authencate the access. </p>

<p>The project need of course to get the metada from the server. This task is done buy a client component of Ez2Cloud that will be run on the on-premise server named Ez2Cloud sattelite service.</p>
</div>
Please for more information see [Ez2Cloud sattelite service](sattelite.md)
<div style='text-align: justify;'> 
<p>The administrator also determine which users and labels will be available to that project, the date that the projected will be archived(users don't access them anymore) and set a notification that will be fired when the project is about to be archived.</p>

<p>All this information provided by the administrator will become accessible in the application's front end for the end users.If the administrator creates a project and assign no users for it, the users won't be able to see this project when they login to their account in the application.</p>
</div>
The following figure illustrate the way you will create projects:

![Create Project](../images/admin/17.png)

And this figure shows how the projects you created will appear for the end users you assign:

![Projects overview](../images/projects1.png)
