# Folders in Casepedia

In Casepedia, a folder is a location where you can store and organize documents.

In the Folder UI, you can:

* Create folders and sub folders
* Add documents to folders and sub folders.
* Assign permission at folder level, sub folder level and also at file level. The users can perform operations on a folder, sub folder or a file based on the permissions assigned.
* View document and document metadata
* Add versions to documents and delete a document version
* Update document metadata information
* Check-in and check-out documents

Folders are of two types:

* Root Folder which is a master folder created by default with the Casepedia deployment.
* Folders and Sub folders that can be created within the Root folder by authorized users.

## Root Folder

The Root folder is the master folder which is created by default when Casepedia is installed and one or more Super User is created with the installation that can access the Root folder and perform various operations.

The default Super User can perform the following operations in the Root folder:

* Authorize Casepedia users for Root folder
* Create folders under Root folder and authorize users

> In addition to the default Super User, the users that are configured as Super Users can also access the Root folder and perform operations accordingly The Administrator or the default Super User can create Super Users in Casepedia Configurations using the Super Users feature.

The Root folder is displayed in Casepedia home page as shown in the following figure:

### Root Folder Permissions

The Super User can authorize Casepedia users that can access the Root folder. The users can perform operations on the Root folder base as per their authorization.

Super Users can authorize either Users or Roles for the Root Folder.

#### **Authorizing Users or Roles**

**To Authorize Users or Roles**

In the Casepedia home page, hover over the Root folder.The Permissions icon is displayed.

Click the icon, the Root Folder Permissions page is displayed.

You can view the following fields in the Root Folder Permissions page:

* Inherited Permissions—Root Folder is the master folder and it is the first folder in the Folder Hierarchy. Hence, Inherited Permissions will be greyed out and also it is not applicable for Root Folder.
* Add Permissions—enables to assign permissions users or roles.
* Local Permissions—enables to assign local permissions. 

##### Authorizing Roles for Root Folder

In the **Permissions** page, select** Role**. 

In the text box, enter a character or a valid role name that exists in BPM and configured in Casepedia, and click the icon.



