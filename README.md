# A03

**Step by Step Tutorial on how to use Git, GitHub, and Webstorm**

**1**.	Install Git on your local machine which can be downloaded at: https://git-scm.com/downloads
**2**.	Create a Github account on https://github.com/join
**3**.	Connect Github with your IDE, in this case Webstorm. Webstorm can be download at https://www.jetbrains.com 
**4**.	In Webstorm, press Ctrl+Alt+S to view system preferences, then select Version Control Git and enter the path to the git.exe file you downloaded in step 1.
**5**.	In Webstorm, go to system preferences and select Appearance & Behavior > System Settings > Passwords. In “KeePass,” select “Database” and then add the location of the password file.
**6**.	Go to your GitHub page on your browser and then click the + sign on the top right and select "Create New Repository"
**7**.	Name the repository what you want your project to be called. This is where the project code and its history of changes will be stored.
**8**.	Make the repository public so other users can see it and add the readme file. Then click “Create”
**9**.	To import a repository from GitHub, open Webstorm and select "Check out from Version Control" on the right-hand side and select “Git”
**10**.	Enter the URL of your repository. For example: "github.com/YourUserName/ProjectName"
**11**.	Enter your username and email. If this is your first time using Github on your local machine you will have to log into your GitHub account
**12**.	A project will open up with the title of the repository. You can now create and edit files within the repository file.
**13**.	When you want to push the edited files to the online repository create a "Commit" using the green checkmark on the top right on the Webstorm window. 
**14**.	 Add a description to your commit describing what that commit is doing
**15**.	"Push" the commit to the online repository by using the shortcut on Webstorm Ctrl+Shift+K
or you can select the "VCS" tab then the "Git" option then select "Push", which is a green arrow pointing up and to the right.

**Definitions**

**GIT** – A free and open source distributed version control system that is used to view, edit, and keep track of changes in source code during software development. Git is a command line tool. 

**GITHUB** – A Git repository hosting service that provides a Web-based graphical interface. Projects on GitHub can be accessed and edited using the Git command line and commands. Users must have an account to manage repositories, contribute to other users’ repositories, and review changes to code. GitHub has many features to help manage group and individual projects, such as documentation, issue tracking, pull requests with code review and comments, and commits history.

**Repository** – The central file storage location where GitHub keeps all the project’s files and the commits history of all those files. Users have access to the files and can edit them. 

**Clone** – Taking an existing repository on GitHub and copying it to create a local copy on your computer.

**Commit** – A change in a file. GitHub keeps track of changes made to the original program/file. Then, it takes the original file and the new file with the changes, compares them, and saves the difference between them. It does not duplicate the code; it simply keeps track of the change and saves that change.
-	Can undo and redo commits from any point in time since the repository was created
-	Should always document clearly what each commit is doing, labeling it task, feature, or fix.

**Push** – Takes a commit made from your local computer and uploads it to the remote repository, Github. Push allows all users contributing to the project to see the updated information.

**Pull** – Updates your local version of the repository from the new version of the remote repository on GitHub. For example, if you are working on a project with other people and someone made a commit to the master branch, you need to download that update to your local repository so you can work on the updated project and not the old version This will prevent conflicts in the code. 

**Branch** – A copy of the master repository. It allows you to make changes to the code without affecting the original master code until you’re ready to commit the changes and merge it with the master code. 

**Merge** – The automatic taking of one branch and its changes and blending it to the main master code. The changes in the file will get saved into the master branch. This is usually done with a pull request.

**Merge Conflict** – Occurs when Git does not know how to automatically merge/blend two files together so the users must merge the code themselves. Typically happens when two users edit the same line of code and saves it or if someone deletes a file that another person is working on. Pull requests will not go through until these conflicts are resolved.

**Fetch** – Gets the most recent changes of the remote repository on GitHub but does not merge it with the repository on your local computer. This allows users to view the new changes and code to compare it to the one stored on their local machine. 

**Remote** – A repository hosted on a server, like GitHub, where users push and pull new changes to the code. 


**References**

Introduction to Github and Webstorm by Arther H Hendela, Ph.D. Senior University Lecturer, NJIT
https://help.github.com/en/articles/github-glossary 
https://www.git-tower.com/learn/git/glossary/remote
https://www.theserverside.com/video/Git-vs-GitHub-What-is-the-difference-between-them
