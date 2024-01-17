# NewHorizonClass0
This is a guide on how to get started with your own GitHub account, repository, and CodeSpace.

Hello, World! Hello, New Horizon Students!
Thank you so much for joining us this semester, and I hope we all have fun throughout the school year. The first few classes may be tough, and you may not know what is going on. No worries. Everything will start to make sense as we progress through the school year.

I will show you how to get started with your own GitHub, repository, and CodeSpace, but you can always come back here to reference anything we may have missed.

If you do see a typo or read something that does not make sense to you or is unclear, please let me know. I would love to either fix it or explain it in a different way.

0. Create a new email. No, not your school one. One you can go ahead and call your professional one. Has anyone ever asked you for your email, and you looked them dead in the face and were like 67892SupremeBapeHead@hotmail.com? 
Not very professional. A professional email should follow this kind of rubric: FirstName.LastName@domain.com. 

Example: Oscar.Rocha@gmail.com, Rocha.Oscar@gmail.com, O.Rocha@gmail.com. If you need some help with this, we can talk after class or through email. 
**Now For The GitHub Account And So Much More**
1. Create your own GitHub account. Use the link https://github.com/ to get started with it. My GitHub account is what you see above. I created a whole new one so we can go through it together and so it is not as intimidating. https://github.com/Oscar-Rocha
  a. You will need access to your email to confirm that you want to make the account

2. **Welcome To GitHub**
Put down "Just Me"
Put down "N/A"
Press next/okay
Select Collaborative coding and continue
Coontinue for free
Boom You are all set with your github account

Keep this account information safe with you!
Note: For some coding concepts, we will be working on GitHub in our CodeSpace.

3. **Creating a Repository**
We want to create a repository. Or in other words a repository contains all of your code, your files, and each file's revision history. You can discuss and manage your work within the repository.
To get started let us follow along with these steps:
Go to your main profile (mine is https://github.com/Oscar-Rocha)
  To get their you can click on your image on the top right and click your      profile
Click on "Repositories"
It should say "doesn’t have any public repositories yet."
Click on "New"
Fill in Repository Name with "NewHorizonClass100" Or "NewHorizonClass100"
Add a description  "This is our first repository and we will either add a few more on continue to work on this one"
Leave it on Public
click on the box that says "Add a README file"
click on the box below Add .gitignore
  Choose the letter C
  box will say ".gitignore template C"
Choose a license will be left alone
  Should say "License: None"
Click on "Create Repository"
CONGRATUALTIONS!!! YOU JUST CRREATED YOU FIRST REPOSITORY
Before moving on click on .gitignore file
click on the pencil icon
delete all lines in this file
should only have 1 line that has words "Ener file contents here" as a preview message
click on commit changes...
a pop will appear and click on commit changes again
click on <>code in top left corner
We are done with **Repository** for now!

4. **Welcome to coding on a browser with CodeSpaces**
What is github CodeSpaces? GitHub Codespaces is an instant, cloud-based development environment that uses a container to provide you with common languages, tools, and utilities for development.

To get started with this follow these steps:
Depending where you are this may differ. But you want to be in your newly created repository. 
Once inside the repository you want to click on the green <>code button
Local means you can use your "coded" files on github desktop
Since we are using chromebooks and mac's we will be using a cloud based enviorment. So not locat.
Click on Codespaces
Click on the green button "Create codespace on main"
Give the new tab a few minutes to get all set up.
What is nice it has all visual studio tools and a great enviorment for developing C# code

**To get started we need command line tools to get C# and .NET on this Codespace**
On terminal in the bottom you should see something along these lines @Oscar-Rocha ➜ /workspaces/NewHorizon100 (main) $ 
we will be using command lines to get our project started
the command line we will be using is called "dotnet" pre installed
**type this in exactly with quotation marks
"dotnet new console -n NewHorizon100" or "dotnet new console -n NewHorizon101"**
What this will do is create a scaffold of the project structure
we will be using dotnet 7
You will see after the pressing enter you will get your terminal project above
For more information "https://learn.microsoft.com/en-us/dotnet/core/tutorials/top-level-templates"

4.5) We have to install some extensions in this program
Click on extensions tab or ctrl+shift+x
look up c# 
We want to install c# Dev Kit
We want to install C#
The program itself may just install it for us

CodeSpace enviorment is nice because we have this available anytime we want to work on this project. And It will install all the tools since it is free.


5)**How to run our code**
In order for us to run our code in this workspace we will have to use the "dotnet" tool
Later on in the course we will not have to do this but we will for now.
Go on to terminal and type "dotnet run"
What happens after we type this?
What just happened was that terminal told us we did not run it in the right directory. So we will have to shift that directory to the class name which is NewHorizon100 or 101
We will have to do the following to get into it
on terminal type "ls"
you should get somehting 
  like NewHorizon0.sln  NewHorizon100  README.md
  type "cd NewHorizon100/" cool thing is you can press tab after New and it should autofil for you
  press enter
  type "ls"
  type "cd NewHorizon100/" again (this time it is the project name)

  Now if we type in dotnet run it should run our program

  **How to commit and push our code to our repository**
  So! This is a virtual workspace. That means it is up in the clouds somewhere. Do you think our work saves by itself? It does not! How do we save it? Not with ctrl+s sadly. We have to commit it and push it to our repository. Similarily to how we fixed our .gitignore file

  Here are the steps on how to do it. You see that icon that has a little blue circle and number? That is our source control. It lets us know how many changes and things we have made throughout our program
  click on the source control icon
  all the things that say "U: on the right are new files we added to our code. we have to press the + icon next to it
After doing + on all they should all be under "Staged Changes"
U means that it is a new file so we need to "ADD" it to our repository
To do so we need to type something along those linies in the message area
"Adding and setting up C#"
Do not click on commit. Click on the arrow pointing down and choose 
"Commit & Push"

Now if we reload our browser on github you will see a new file with everything we have worked on
