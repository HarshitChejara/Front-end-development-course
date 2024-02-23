----------------------
Software collaboration
----------------------




* Introduction *

1) - Version Control
Version control is a system that records all changes and modifications to files for tracking purposes. The primary goal of any version control system is to keep track of changes. It achieves this by allowing developers access to the entire change history with the ability to revert or roll back to a previous state or point in time. It allows the team to submit their code and keep track of any changes that need to be made.
There are many different version control systems available. For example, Subversion, Perforce, AWS Code Commit, Mercurial, and Git etc.
There are two types version control Centralized version control systems and distributed version control systems. 

2) - Centralized version control systems
It contain a server and a client. The server contains the main repository that houses the full history of versions of the code base. here the server is the central copy of the project. After making changes to the code, the developer needs to push the changes to the central server so that other developers can see them.

3) - Distributed version control systems
This is similar to the centralized model. You still need to pull code down from the server to view the latest changes. The key difference is that every user is essentially a server and not a client. This means that every time you pull down code from the distributed model, you have the entire history of changes on your local system. 

4) - A history of revisions
The history will show who made the change, for what reason, the code itself and its changes, and the date and time of when they occurred. Typically on a new project, you will encounter changes in one task that may cause potential issues or conflicts with another. The history of revisions will give the team the ability to manage and merge these changes and deliver the business objectives in a timely manner.

5) - Staging
The staging environment should mimic your production environment. The reason for this is because you want to test the code in an environment that matches what you have in production. This allows teams to spot or find any potential issues prior to them getting to production.

6) - Production
Production is live. It's out there for people to see and/or interact with. Any issues or problems you may have had should have been caught and fixed in the staging environment. The staging area gives the team a safety net to catch these possible issues. Any code that is deployed to production should have been tested and verified before the deployment itself. 