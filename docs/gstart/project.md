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
<p> When creating a project it is defined which users and labels will be available. Also there are settings like date that the projected will be archived and notification that will be fired when the project is about to be archived.</p>
<p>The project as a base unit of work will be available and, in the context of the implemented proces,s the application front end delivers features and functionalities to end users. So all users assigned to a project after logged in can view it and completed task based on data the project have.</p>

<hr>
</div>

## Projects in Ez2Cloud
1. [View Projects](viewprojects.md)
     1. [Active Projects](activeprojects.md)
     2. [Archived Projects](archivedprojects.md)
2. [Create New Project](../projects/createnew.md)
     1. [Assign labels information](../projects/assignlabel.md)
     2. [Assign owners information](../projects/assignowner.md)
3. [Colaborative Work in Projects](../projects/colaborative.md)
