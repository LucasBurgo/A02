<h1>How to setup Git, Github, and WebStorm:</h1>

<h2>Step 1: Install Git</h2>
<ol>
<li> Download Git from the official website : https://git-scm.com/downloads</li>
  
<li> Follow the installation instructions for your operating system.</li>
</ol>

<h2>Step 2: Create a GitHub Account</h2>
<ol>
<li>Go to https://GitHub.com and sign up for a free account.</li>
  
<li>Follow the prompts to complete the registration process.</li>
</ol>

<h2>Step 3: Set Up Git</h2>
<ol>
<li>Open a terminal or command prompt.</li>

<li>Configure your Git username and email:</li>

git config --global user.name "Your Name"

git config --global user.email "your.email@example.com"
</ol>


<h2>Step 4: Create a New Repository on GitHub</h2>
<ol>
<li>Log in to your GitHub account.</li>

<li>Click on the "New repository" button.</li>

<li>Enter the repository name (e.g., MyProject) and a description (optional).</li>

<li>Select "Public" or "Private" depending on your preference.</li>

<li>Click "Create repository."</li>
</ol>

<h2>Step 5: Clone the Repository</h2>
<ol>
<li>Copy the repository URL from GitHub.</li>

<li>Open a terminal or command prompt.</li>

<li>Run the following command to clone the repository to your local machine: git clone https://github.com/yourusername/MyProject.git</li>
</ol>

<h1>Part 2: Using WebStorm</h1>

<h2>Step 6: Install WebStorm</h2>
<ol>
<li>Download WebStorm from the official website: https://www.jetbrains.com/webstorm/download/#section=windows</li>

<li>Follow the installation instructions for your operating system.</li>
</ol>

<h2>Step 7: Open the Repository in WebStorm</h2>
<ol>
<li>Open WebStorm.</li>

<li>Click on "Open" and navigate to the directory where you cloned the repository.</li>

<li>Select the repository folder and click "Open."</li>
</ol>

<h2>Step 8: Make Changes to Your Code</h2>
<ol>
  <li>Use WebStorm's editor to make changes to your code.</li>
  
  <li>Save your changes.</li>
</ol>

<h2>Step 9: Commit Your Changes</h2>
<ol>
  <li>Open a terminal or use the built-in terminal in WebStorm.</li>
  
  <li>Stage your changes: git add .</li>
  
  <li>Commit your changes: git commit -m "Describe your changes here"</li>
</ol>

<h2>Step 10: Push Your Changes to GitHub</h2>
<ol>
  <li>Push your changes to the remote repository: git push origin main</li>
</ol>

<h1>Glossary</h1>
<ul>
<li><strong>Branch</strong> - The copy of a code that would divege from the main code, used by developers to fix or improve their code.</li>
  
<li><strong>Clone</strong> - A clone would mean creating a copy of a repository from a remote server.</li>

<li><strong>Commit</strong> - An action that saved the code.</li>

<li><strong>Fetch</strong> - The process of receiving updates from the remote repository to your local repository.</li>

<li><strong>GIT</strong> - A distributed version control system that helps the developer manage their code.</li>

<li><strong>Github</strong> - A web-based platform that uses Git for version control.</li>

<li><strong>Merge</strong> - The process of combining changes from different branches into a single branch.</li>

<li><strong>Merge Conflict</strong> - Occurs when changes from different branches of a codebase are in conflict and cannot be automatically merged.</li>

<li><strong>Push</strong> - The action of sending your local commits to a remote repository.</li>

<li><strong>Pull</strong> - The action of fetching and integrating changes from a remote repository into your local repository.</li>

<li><strong>Remote</strong> - A version of a repository that is hosted on a server, typically over the internet.</li>

<li><strong>Repository</strong> - A storage location for software packages, code, files, and their history.</li>
</ul>
