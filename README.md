My First Angular Project

Here I go.

So, You will love to use the integrated git source control of the Visual Studio Code. For that I have just download the git for Windows from the very official site. (https://git-scm.com/) If you are using the Windows OS you can directly go to https://git-scm.com/download/win .

Just download it and you are ready to roll the changes to your gihub directly through the Visual Studio Code editor.

Also, one more things to remember, Don't forget to run this command in powershell (Run powershell as administrator), to execute all the Angular CLI command through cmd or Visual Code Terminal : Set-ExecutionPolicy RemoteSigned


## All About Angular Project Structure Now
src Folder : You will find all the files related to project will be find here.

## Components
Yes now you can make the componenets just using the commands `ng g c abc`. It is the abbreviation of the commands of the ng genrate component abc

To make the components nested under one components, you can simply use `ng g c abc/xyz`

You can see all the components under the app folder in the src.

And yes, if you dont want to add any of the folders for the component, you can simply use the `ng g c components --flat` This command will create a component with the name of the components without a folder.

Use dry run options to see the list of files and folders that will be generated without creating any files and folders. For example : `ng g c ghi -d`

-d is an alias for the dry run options

## Service
To create the service is very similar to the creating the components. Use the commands ng g s customer for the service.

But remember your service won't register automtically. There are two ways to register it now :

1) Manual
2) Or by instructing the Angular CLI to register it with specific module.