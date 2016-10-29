# Setup-GitHub-With-VS-Code
How to set up Github for use with Visual Studio Code on Windows

I had a difficult time setting up Github for use with Visual Studio Code but eventually found [this article](http://michaelcrump.net/using-github-with-visualstudio-code/) describing how to do it on OSX.

My severe lack of knowledge led to the instructions not actually working but they did lead to the following steps which work for me. I'm including them here because I keep forgetting details of the procedure.

1. Use the Git tab/function in Visual Studio Code to put the project's folder under Git control.
2. Go to https://github.com and create a new project.
3. Click the **Clone or download** button and copy address of new git.
3. Open a terminal window and navigate to the location of the project.
4. Enter the following: `git remote add origin {copied_git_address}`.
5. Open GitHub Desktop and click **+** button in upper left corner.
6. Click **Add** then enter local path to project folder (use **Browse** button).
7. Click **Add repository** button.
8. Project can now be synced from within VSC.
