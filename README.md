# A02
Aidan Heaney

PART 1: Step-by-Step Setup Tutorial
Step 1: Install Git using this link: git-scm.com/downloads.
Choose the download for your operating system (Windows, macOS, or Linux).
Run the installer, leaving all default settings as they are, and click through to finish.
Open your computer's terminal (or Git Bash on Windows) and type git --version. If a version number prints out, the installation was successful.

Step 2: Set Up Your GitHub Account
Go to github.com/signup.
Enter your email, create a password, and pick a unique username.
Follow the prompts to verify your email address.

Step 3: Download Your Preferred IDE
For WebStorm: Visit JetBrains' website to download WebStorm. Run the installer. (Note: You can use your student email to register for a free JetBrains educational license).
For VS Code: Visit code.visualstudio.com, download the installer, and run it using the default settings.

Step 4: Create a Remote Repository
Log into your new GitHub account.
Click the + icon in the upper-right corner and select New repository.
Name the repository A02.
Set the visibility to Public.
Check the box to Add a README file.
Click the green Create repository button.

Step 5: Clone the Repository to Your Computer
On your new GitHub repository page, click the green Code button and copy the HTTPS URL provided.
If using VS Code / Terminal:
Open your terminal and use the cd command to navigate to where you want to save the folder (e.g., cd Documents).
Type git clone <paste-your-URL-here> and hit Enter. This creates an A02 folder on your machine.
Open VS Code, click File → Open Folder, and select your new A02 folder.
If using WebStorm:
Open WebStorm, click File → New → Project from Version Control.
Paste the copied GitHub URL into the URL box, choose your destination folder, and click Clone.

Step 6: Configure Git Identity & Connect Accounts
In VS Code: Open the integrated terminal (Terminal → New Terminal) and configure your identity by running:
git config user.name "Your First and Last Name"
git config user.email "your.email@example.com"
In WebStorm: Go to Settings (or Preferences on Mac) → Version Control → GitHub. Click the + button to log in via GitHub and authorize the IDE to connect to your account.

Step 7: Make Changes and Commit
Open the README.md file in your IDE's file explorer.
Type a brief description of the project into the file and save it (Ctrl+S / Cmd+S).
In VS Code: Open the terminal and type git add . to stage the file, then type git commit -m "Updated README description" to save a snapshot of the change.
In WebStorm: Open the Git menu and click Commit (or press Ctrl+K). Type a descriptive commit message in the prompt and click Commit.

Step 8: Push Your Changes to GitHub
In VS Code: In the terminal, type git push origin main.
In WebStorm: Go to Git → Push (or press Ctrl+Shift+K), review the changes, and click Push.
Return to your repository page on GitHub.com and refresh your browser. You should now see the text you added to the README file live on the web.

PART 2: Version Control Glossary
Branch: An independent, parallel line of development within a repository. Branches allow developers to build new features or experiment without breaking the main, working codebase.
Clone: The action of downloading a complete copy of a remote repository from the cloud (like GitHub) directly to your local computer.
Commit: A saved snapshot of your project files at a specific point in time. It always includes a brief text message explaining what modifications were made.
Fetch: Downloading the latest data and commit history from a remote repository to see what others have done, without actually merging those changes into your current working files.
GIT: A widely used, free, and open-source distributed version control system designed to track file modifications and coordinate multiple developers working on the same project.
GitHub: A cloud-based hosting platform for Git repositories. It provides a visual interface and collaborative tools like issue tracking, project boards, and pull requests.
Merge: The process of taking the code changes from one branch and integrating them into another branch.
Merge Conflict: An issue that triggers when Git cannot figure out how to automatically combine changes because two people edited the exact same line of code in conflicting ways. The developer must manually choose which code to keep.
Pull: A combination command that both downloads (fetches) the latest changes from a remote repository and immediately integrates (merges) them into your active local branch.
Push: The act of uploading your locally saved commits up to a remote repository (like GitHub) so that the rest of your team can see and access them.
Remote: A version of your project repository that is hosted externally on a server (e.g., GitHub), acting as a central hub to push to and pull from.
Repository (Repo): A specific storage directory that holds all of your project's files, folders, and the entire historical timeline of changes tracked by Git.
