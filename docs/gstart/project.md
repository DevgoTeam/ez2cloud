## Project
<div style='text-align: justify;'>
<p>Project is defined as a collection of files and folders plus the metada on a specific server network shared folder. 
Project it is the unit of data that users will work in a distrubted and colaborative approach and it encapsulate a network shared folder metada providing all the users with access to that network shared folder a structured and user-friendly view on it from the Ez2Cloud interface. Before any activity the Ez2cloud admin user from your company must create a project that will be the starting point where users can view and label the files and folders.</p>

<p>The concept it is realized with two differents approaches: First the project must be defined and set. This is done on the backend only by a user with Administratr role. After the configuration and setting for a project it is done it will be available to colaborative works. So this will be the second approach where project it is the basic unit of work and users accessing projects  on the end-user interface.</p>

<p>Only a user with Administrator or Project Administrator role can add a new project. When doing so, it is mandatory to provide a name, description, an end date. Also the project as it the view from Ez2Cloud to a shared network folder on create the project it is mandatory to define local network path. This is the absolute path to a folder on the company File Server. If need the project must also get user name and password to authencate the access.</p>

<p>As represented on Ez2Cloud, a project gets files and folders metada from a company file server. This process is performed by a component of Ez2Cloud that will be run on on-premise server named Ez2Cloud sattelite service.</p>
</div>
For more information, please see [Ez2Cloud sattelite service](sattelite.md)

<div style='text-align: justify;'>
<p>When creating a project it is defined which users and labels will be available. Also there are settings like date that the projected will be archived and notification that will be fired when the project is about to be archived.</p>

<p>All this information tor will become accessible in the application's front end for the end users.If the administrator creates a project and assign no users for it, the users won't be able to see this project when they login to their account in the application.</p>
</div>


## WorkingwithProjects

* [Create new Project](sattelite.md)
* [Upload Metada to Project](sattelite.md)
* [Edit Project](sattelite.md)
* [Projects on File Explorer](sattelite.md)

