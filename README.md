[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/GvXCZgfk)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-2e0aaae1b6195c2367325f4f02e2d04e9abb55f0b24a779b69b11b9e10269abc.svg)](https://classroom.github.com/online_ide?assignment_repo_id=15361245&assignment_repo_type=AssignmentRepo)
# SE-Assignment-4
Assignment: GitHub and Visual Studio
Instructions:
Answer the following questions based on your understanding of GitHub and Visual Studio. Provide detailed explanations and examples where appropriate.

Questions:
Introduction to GitHub:

What is GitHub, and what are its primary functions and features? Explain how it supports collaborative software development.

GitHub is a version control system supported by Git that not only allows developers to work on the same code, but also facilitates collaboration between them. Its Key Features & Functionalities 

Key Functions & Features: 

Version Control: 

Source Control Github Backs Powerful Version Controlling Using Git Developers can Follow to Change Codebase Roll back over Different Previous Updated & Manage Several Versions of Projects at A Time 

Repositories: 
All the projects are grouped by repositories (repos). The content of each repository: all files from the project + history what and when has changed. 

Branching and Merging: 
Branches are used for isolating work (feature, bug fix or experiment) from the main codebase. They can be finally merged back to main branch post review.
Pull Requests:

Pull requests are one of the main features of GitHub that allow developers to propose changes in a codebase. These changes can be collectively examined, discussed and approved by team members before merging them to the main branch.

Issue Tracking:

Issue tracking - helps Github users to report bugs, suggest improvements and so on as well managing your tasks. Tickets support labeling, assigning to team members and linking them directly to code changes.

CI/CD (Continuous Integration, Continuous Deployment)

Github offers Integration with CI/CD tools across the industry to automatically test and deploy changes, thereby making absolutely certain that any change made to your codebase doesn't break what is already there.

Communication and collaboration:

GitHub features include project boards, team discussions, code review tools and more. These features help with communication and collaboration between team members.

GitHub for Collaborative Software Development

Centralized Codebase:

By facilitating a centralized platform for all team members to get the latest version of codebase on GitHub, it guarantees that everyone is working with the most updated code.

One engages the code developed by other team members, making sure it runs in a reliable way for which only honest reviewers should be involved.

Code Reviews and Pull Requests - While writing the code is just one part of maintaining a good quality level in coding. They can review work done by other team members, give feedback and ensure that it is up to the project standard before being deployed.

Distributed Workflow:

GitHub has rich support for branching and merging which naturally enforces distributed workflows, allowing developers to work on various parts of a project at the same time without stepping all over one another's foot.

Internal Transparency and Accountability:

A full history of changes, commits and issues gives clear insight into what was changed by whom for which reason. This creates a state that is accountable and easier for you

Repositories on GitHub:

What is a GitHub repository? Describe how to create a new repository and the essential elements that should be included in it.

A GitHub repository, also known as a repo serves as a storage space, on GitHub where your projects files and their revision history are stored. It enables developers to handle and collaborate on code, housing project related content like folders, files, images, videos along with the record of changes made to these files.
Steps to Establish a GitHub Repository;
1. Sign in to your GitHub account by visiting github.com.
2. Create a repository by clicking on the "icon located at the top right corner of the page and selecting "New repository."
3. Configure Repository Settings;
   Provide a name for the repository.
    Optionally include a description.
Select the visibility of the repository; Public ( to everyone) or Private (accessible, to you and collaborators).
Finally, a readme file can be added then click on create repo.
Some of the essential elements of a repo include;
	A README.md file
   .gitignore
	A license
	Code files

Version Control with Git:

Explain the concept of version control in the context of Git. How does GitHub enhance version control for developers?

Version control is the process of keeping track of all changes made to a file or set of files over time. The clue to that is being able to recall either the original or any other. It is a system used to audit changes of a file or set of files over a project timeline so that team members working on the same project could identify changes and know that work is kept intact, not overwritten. Git is a Distributed Version Control System that enriches version control with tools efficiently managing and monitoring changes within a project. 
Examples of how Git improves version control; 
Distributed System; 
Git works decentralized. Everyone has a copy of the repository but also the history of that repository on their laptop. 
Branching and Merging; 
Anyone can use Git to create branches to implement features/fix bugs, without affecting the real codebase. 
Staging Area; 
Incorporates a so-called staging area or index, where you include files in order and review changes before committing them for good. 
Commit History; 
Basically, whenever changes are introduced, they get recorded as commits. In this respect, this allows tracing of the changes. 
Version Control; 
Enables reverting of files or whole projects to the previous state; thereby allowing to debug.

Branching and Merging in GitHub:

What are branches in GitHub, and why are they important? Describe the process of creating a branch, making changes, and merging it back into the main branch.

GitHub branches, just like Git branches, represent parallel versions to a project. These versions give one the space to deal with the development of different features, fixing of bugs, or even trying out different experiments on a piece of code independent of the core source code. Branches become very important since they allow the working of different developers on different tasks without messing up each other's work. 
Importance of Branches 
Isolation of Work:
In this, every branch is an independent line of development; hence, making changes in one branch does not affect the main or other branches. 
Facilitate Collaboration;
Many developers can work on different features or fixes simultaneously without facing any conflicts. 
Safe Experimentation:
 This allows developers to play with new ideas or technologies in a branch, or basically try out anything, without affecting the stability of the main codebase. 
Organized Workflow: 
One of the instrumentations that are very essential to having work organized is branches. They keep new features, bug fixes, and experiments aside from the main branch until it is ready for merging. 

Process of Creating a Branch, Making Changes, and Merging 
Creating a Branch: 
Go to your repository in GitHub. click on the branch dropdown 
Type a new branch name and press "Enter" or click 
Switch to the new branch and make your changes on the code, stage the changes then commit them before pushing then performing a pull request

Pull Requests and Code Reviews:

What is a pull request in GitHub, and how does it facilitate code reviews and collaboration? Outline the steps to create and review a pull request.

A pull request in this case is a way a developer alerts his or her colleagues  to changes that were made in a branch concerning a repository on GitHub for further review and collaboration. Team members can make comments and observe the suggested changes before they are added or actually integrated into the main code. 
How Pull Requests Facilitate Code Reviews and Collaboration 
Code Review;
Proves to be a platform where developers can comment on each other's code, pointing out shortcomings in them and discovering bugs before finally merging changes into the main branch. 
Discussion and Feedback: 
The Team members are able to comment, ask queries and reply directly to specific lines in PR. 
Change documentation:
PRs record what changes were made, why they were made, and who did them. This keeps the history of the project clean. 
Automated Checks: 
Integrations with CI/CD tools can run automated tests and checks over the changes proposed within a PR for the quality and standards of code.
Steps of Creating and Reviewing a Pull Request
Create a Pull Request
Make Changes in a Branch:
Make sure you are not in the main branch.
Change your code, commit it, and push the branch to GitHub.

Go to the Repository:
Go to your repository on GitHub.
Open Pull Requests Tab:
Click on the "Pull requests" tab at the top of the repository page.

Create a New Pull Request:
Click the "New pull request" button.
Select the branch you want to merge into the base branch, usually main or master.

Compare Changes:
Check the changes between the branches.
Click "Create pull request".

Fill in Pull Request Details:
Write a descriptive title and detailed description of what has been done in the PR.
Assign reviewers, labels, milestones.
Click "Create pull request" to submit the pull request.

Reviewing a Pull Request
Open the Pull Request:
Head to the "Pull requests" tab in the repository.
Click on the pull request you are going to be reviewing.

Viewing Changes
Click on the "Files changed" tab and then view the diffs.
Add comments to specific lines of code to make a comment. .

Approving or Requesting Changes
You can approve, request changes, or comment on a PR after you finished reviewing the changes.
Hit the "Review changes" button, then select "Approve", "Request changes" or "Comment".
Once your PR is approved and you addressed the requested changes, close it by merging it.
Click on the green button "Merge pull request".
Confirm the merge, click on "Confirm merge

GitHub Actions:

Explain what GitHub Actions are and how they can be used to automate workflows. Provide an example of a simple CI/CD pipeline using GitHub Actions.

GitHub Actions is one of the features in GitHub for automating workflows right inside the repositories. It gives developers the ability to create software development lifecycle custom workflows, including continuous integration and continuous deployment. You can use it to automate testing, build-and-deploy code, and much more.

How GitHub Actions Are Enabling Automated Workflows
Continuous Integration CI: Automatic test and checking of your code on every push of a change into the repository.
Continuous Deployment CD: Every time changes make it into the main branch, automation of deployment for your application happens in different environments.
Custom Workflows: Automate any repetitive task in your development process—be it code linting, generating docs, or updating dependencies.
Event-driven: Integrate along workflows on events like push, pull request, creation of the issue, and so on.

Introduction to Visual Studio:

What is Visual Studio, and what are its key features? How does it differ from Visual Studio Code?

Visual Studio is a development environment, developed by Microsoft, to create, debug, and deploy applications on Windows, on the web, and on mobiles.
Key Features:
Development Tools: Facilitates development in a number of languages, which include C#, C++, Python, JavaScript.
Advanced Debugging and Diagnostics: Thorough tools for debugging, profiling, and running diagnostics smoothly.
Integrated Development Tools: Has an in-built suite of tools for database development, web development, and mobile app development.
Version Control System Integration:
Git, Subversion, and other version control systems.
Extensions and Customization: A fine market of extensions to extend its capabilities.
Collaboration: Contained set of instruments for Agile project management procedures and collaborative work, for example, Azure DevOps.
Visual Studio Code
Visual Studio Code, or VS Code, is another creation from Microsoft. VS Code is an open-source code editor, free and lightweight. It is used for editing codes; it is fast and straightforward to use.
Differences:
Purpose: Visual Studio is a full-fledged IDE for major projects, and VS Code is lightweight in order to be a code editor for fast and light edits and smaller projects. 
Performance: VS Code is faster and also consumes fewer resources compared to Visual Studio. 
Extensibility: On the evolution side, both are highly extensible, and thus, Visual Studio contains more built-in enterprise-level development capabilities. 
Platform Support: VS Code is cross-platform; Visual Studio moved mostly to the Windows platform, albeit there is a macOS version as well.

Integrating GitHub with Visual Studio:

Describe the steps to integrate a GitHub repository with Visual Studio. How does this integration enhance the development workflow?

Install Git and Visual Studio:
Download and install Git if it's not already installed on your system.
Install Visual Studio; inside the installation process, make sure to choose a workload that includes Git support.
Clone Repository:
Open Visual Studio.
Go to File > Clone Repository.
Input your repository URL on GitHub and specify a local path.
Press Clone.

Create or Open a Project:
Open an existing project or create a new one in the cloned repository.

Commit and Push:
In the Team Explorer pane, see changes | Stage files | Commit
Click Sync to push these changes to GitHub.

Pull and Fetch Updates:
Pull will get all the updates from the remote repository.
Fetch allows a user to look at the changes on the remote without merging.

Branch Management:
In the Team Explorer pane, create and switch branches.
Merge branches; Resolve conflicts if any occurs.

How Integration Enhances Development Workflow
Streamlined Collaboration: Share code easily with team members for collaboration purposes.
Version Control: Any changes can get traced and roll back to versions if need be. This keeps track of all key changes made to a codebase over time.
Management of Branches: Work on features and bug fixes simultaneously without impeding the main codebase.
Resolve Merge Conflicts: Efficiently merge and resolve these conflicts.
Continuous Integration: Integrate with automated CI/CD pipelines for testing and deployment.

Debugging in Visual Studio:

Explain the debugging tools available in Visual Studio. How can developers use these tools to identify and fix issues in their code?

Breakpoints:
Set Breakpoints: Runs the code to a particular line then pauses it.
Conditional Breakpoints: Setting breakpoints where it gets paused only when conditions are met.
Function Breakpoints: It pauses the execution when the point in called function is reached.
Data Breakpoints: It pauses the execution on a change of a variable's value.

Watch Windows:
Watch: Views variables and expressions, how their values are changing during execution.
QuickWatch: Temporarily view variables and expressions.

Locals and Autos Windows:
Autos: The variables in the current scope are visible.
Locals: These are the variables used in the current line and the previous line of code.
Call Stack Window:

Show a call stack of the functions called leading up to the current execution point.
Immediate Window:
Here you can enter commands and evaluate expressions while debugging.
Output Window:
Here you get most of your output of debug messages, build errors, and several other diagnostic information.
Exception Settings:
Now configure Visual Studio to break upon throwing or unhandled exceptions.
Diagnostic Tools:
CPU Usage: The real-time CPU usage can be viewed during Debugging.
Memory Usage: Observe the Use of Memory, Allocation, Detecting Memory Leaks and Gains in Performance. Edit and Continue:


How to Use Debugging Tools to Detect and Fix Issues
Putting Breakpoints

Set breakpoints on suspicious lines of code; execution will halt so that you can inspect the state of your application.
Call Stack:
Investigate the call stack to see what series of function calls resulted in this state, and identify at which point things went wrong. Step through the call stack. Inspect other frames and their local variables.
Handling Exceptions:
Set your exception settings for it to break on a particular exception and then investigate where that exception is thrown; that is, the state your app is in.
Diagnostic Tools:
Monitor CPU and memory usage for performance bottlenecks and memory leaks. The information obtained from these tools can be used to enable the application to work efficiently. 

Collaborative Development using GitHub and Visual Studio:

Discuss how GitHub and Visual Studio can be used together to support collaborative development. Provide a real-world example of a project that benefits from this integration.

Repository Management: The project repository is to be hosted on GitHub.
Cloning and Syncing: Clone the repository in Visual Studio and always be keeping it in sync with GitHub.
Branching: New features or bug fixes to be worked on separate created branches.
Pull Requests: Collaborate on code via pull requests which allow code reviews and subsequent discussions.
Commit and Push: Committing changes locally, then pushing them to GitHub will be done through Visual Studio.
Track the bugs and features on the GitHub platform. It's capable of linking them with a commit or a pull request. 
Continuous Integration: Connect to continuous integration and continuous deployment tools to automate test and deployment methodologies. 
Real-World Example:

Open-Source Project - Visual Studio Code:
Repository: Its repository is available on GitHub. Anybody anywhere in the world can collaborate.
Development: The developers at Visual Studio use this to clone, develop and debug.
Collaboration: Contributors create new features in branches, make pull requests, and have code viewed.
CI/CD: The auto build run tests, making sure that it's stable before merging changes.
Benefits:

Services such as draft sharing enable easy code sharing and hence easier collaboration.
Quality Control: This ensures high-quality code through code review and CI/CD.
Transparency: Development history, discussions regarding the GitHub issues, pull request


Submission Guidelines:
Your answers should be well-structured, concise, and to the point.
Provide real-world examples or case studies wherever possible.
Cite any references or sources you use in your answers.
Submit your completed assignment by [due date].
