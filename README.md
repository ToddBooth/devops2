Hello Students,

## Reporting your results

As you do each hands-on lab, please document which is the last hands-on lab that you completed. That will allow Teacher Todd to monitor which students need help and will allow us to understand how many of the students have completed each assignment.

Please update the Student Information spreadsheet ([Link](https://1drv.ms/x/s!AoKzBdVhxRgZhuFJxesdzIKFQuvEYg?e=zvhKby)) with the last lab number that you completed, after completing each hands-on lab.

## List of the hands-on labs

Please keep a web browser tab dedicated to this Wiki hands-on lab web page, to save you time.

### Hands-on Lab 101 - Update the Student Information spreadsheet with your personal email address

I need to add all students to my Azure DevOps Organization's Project, so that you can see the project Wiki, with the relevant information you need concerning this course. For example, I need to give you access to hands-on lab instructions.

The only person who will have access to this information is Teacher Todd and he will delete this student information after authorizing you to access the project Wiki.

Verify that you lack authorization to access the DevOps course Wiki ([Link](https://toddbooth.visualstudio.com/DevOps_Architecture_Course/_wiki/wikis/DevOps.wiki/1/DevOps-Architecture-Course)).

Then please update the Student Information spreadsheet ([Link](https://1drv.ms/x/s!AoKzBdVhxRgZhuFJxesdzIKFQuvEYg?e=zvhKby)) with your personal email address. Keep this spreadsheet in its own browser tab, to make things easier. 

After Teacher Todd authorizes you to access the DevOps courses WiKi, he will let you know and then you will be able to access the Wiki ([Link](https://toddbooth.visualstudio.com/DevOps_Architecture_Course/_wiki/wikis/DevOps.wiki/1/DevOps-Architecture-Course)).

Even before you can access the Wiki, please update the Student Information spreadsheet, stating that you completed this lab 101.

### Hands-on Lab 102 - Create your Azure user account

We assume that your company does not want you to use your company issued Azure user account for training and testing, so for this hands-on lab, we would like you to create your own personal Azure user account, with your own personal email.  If your personal email is not associated with a Microsoft email account, Microsoft will ask you to associate your personal email address with Microsoft. 

A credit card is required to verify your identity. It will not be charged unless you opt in to pay.  By signing up you will receive $200USD/Euro in credits, to use your first month. After that, Azure gives you a lot of free services, including some free DevOps services ([Link](https://portal.azure.com)).

Also, by having a private Azure account, if you want, you can learn in your personal time. Your company might also allow you to access your private Azure account, while at work, to help you learn Azure DevOps better and to prepare you for a conversion by your company to Azure DevOps.

It is suggested that as we have all the hands-on lab, you perform the actions on your own person Azure DevOps account, instead of just watching another student perform the actions. If you are stuck, your study buddy and I will help you with any problem that comes up.

Please update the Student Information spreadsheet.

### Hands-on Lab 103 - Create your Azure DevOps organization and first project

Note that for a single Azure user account, you can create and have multiple DevOps organizations.

For each Azure DevOps organization, you can have multiple projects.

After you login to Azure, in the services field, enter "DevOps", choose "DevOps" organization, surf there, choose New Organization, and give it a name (which must be globally unique), such as "Org-" followed by 4-8 random digits. Please don't include blanks since the URL will look strange. 

It will ask for a project name (which does not need to be globally unique), so choose "devops-course-01", or whatever you want. Again, don't use blanks.  Make the project "private".

Please update the Student Information spreadsheet.

### Hands-on Lab 104 - Organization settings

Go to the first DevOps organization, click on the lower left "Settings" and try to learn what all of the setting choices are, what they mean, and when you would use them.

Please update the Student Information spreadsheet.

### Hands-on Lab 105 - Project settings

Go to the first DevOps organization's first project, click on the lower left "Settings" and try to learn what all of the setting choices are, what they mean, and when you would use them.

Please update the Student Information spreadsheet.

### Hands-on Lab 106 - Create 2nd DevOps project

In the first DevOps organization, create a second project named "devops-course-02".

Please update the Student Information spreadsheet.

### Hands-on Lab 107 - Create 2nd Organization

Create a 2nd DevOps Organization with the previous organization name, and then append "-02".

Name the project the same as you used before.

Please update the Student Information spreadsheet.

### Hands-on Lab 108 - Create 2nd DevOps Repo

When you create a DevOps project, it creates the first default DevOps Repos repository. In one project, you can have more than one repository, and that is quite common. So, in this lab, you will create a second DevOps Repos repository. Name it repo-102.

Please update the Student Information spreadsheet.

### Hands-on Lab 109 - Choose an IDE

For this course, you will need an IDE for some of the following: Java programs, Python scripts, C# programs, JavaScript, bash scripts, and yaml files. If you want, you can use the IDE on your company issued client computer or on your company issued VDI instance. Perhaps that would be JetBrains IntelliJ, JetBrains PyCharm, JetBrains WebStorm, Visual Studio 2022, and/or Visual Studio.

However, any company issued device IDE will limit what you can do. If you hit a company limitation during this course, that you want to bypass, then I recommend that you use a cloud-based IDE, like the free GitHub Codespaces IDE, which includes a web-based version of Visual Studio Codespaces.

Also, if you want to learn on your own after this class, even during work hours, I recommend that you use a free cloud-based IDE during this course, so that you can learn how to use it. That way, as soon as the course is over, you can continue in your free cloud-based IDE and keep learning more about Azure DevOps.

GitHub gives you a free 60 hours per month, for a dual core virtual CPU docker container.

If you would like to use the free GitHub Codespaces IDE, please follow these instructions:

1. If you don't have one, please create a personal GitHub account ([Link](https://github.com))
2. Create a GitHub private repository 
3. Create a GitHub Codespace for that specific private repository
4. Start the Codespace
5. Connect to the Codespace
6. Now you can use the vs code web-based editor and you will have a Linux docker container runtime

### Hands-on Lab 110 - Choose a runtime environment

We will use the Azure DevOps runtime environment for our CI/CD pipeline jobs. However, you should also have another one or two runtime environments for initial unit/component testing.

If you are satisfied with your local client's runtime environment, that is fine. 

However, if you are not satisfied, and you want a Linux type runtime environment, you can also use the free GitHub Codespaces Linux runtime environment, even if you are performing local development with a local IDE. 

Visual Studio Code and JetBrains IntelliJ support a local IDE client connecting to a remote GitHub Codespace Linux runtime, via SSH. What this means is that when you click run in your local IDE, the execution occurs in the remote GitHub Codespace Linux runtime.

JetBrains IntelliJ and Visual Studio Code also support a remote Windows runtime. If you want a remote Windows runtime, you need to configure the Windows system to include an SSH server.  You need to also configure the IDE to connect to the Windows system via SSH.

### Hands-on Lab 111 - Connect to the Azure DevOps Repos

In this lab, from your IDE (Windows client, MacOS client, cloud-based IDE), please connect to the Azure DevOps 1st organization's 1st project, via SSH, and via the CLI.

You are required to first connect with a shell command such as "ssh devops", and to resolve the alias "devops" and set all the ssh client configuration parameters, you are required to configure an ssh client ~/.ssh/config stanza to provide all required information.

If you have any problems connecting from your ssh client to the DevOps repo server, you are required to try and debug using a command, similar to the following:

ssh -v devops

Regards, Teacher Todd
