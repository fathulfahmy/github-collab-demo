GitHub colllaboration repository demo for beginners

### Prerequisites

Please install `Visual Studio Code` and `Git`

## Initial setup

Link VS Code with GitHub

<ol>
<li>Open VS Code extension from the left sidebar or <code>ctrl+shift+x</code></li>
<li>Search <code>Github Pull Requests and Issues</code> and install extesnion</li>
<li>Click on github icon from the left sidebar</li>
<li>Click Sign In button</li>
<li>Sign in wtih your GitHub account</li>
<li>Your VS Code is now linked with your GitHub account!</li>
</ol>

Clone github repository

<ol>
<li>Open VS Code</li>
<li>Open command pallette <code>ctrl+shift+p</code></li>
<li>Type <code>git clone</code> and select <code>Git: Clone</code></li>
<li>Select <code>Clone from GitHub</code></li>
<li>Type <code>username/repository-name</code></li>
<li>Select location to store shared code</li>
<li>You have just copied a folder from GitHub and store it in your computer!</li>
</ol>

Open folder in VS Code

<ol>
<li>Open VS Code</li>
<li>Select <code>File</code> on top left corner</li>
<li>Select <code>Open Folder...</code></li>
<li>Select folder that you have cloned</li>
</ol>

Create branch

<ol>
<li>Click synchronize button on bottom left corner beside <code>main</code></li>
<li>Click <code>main</code></li>
<li>Select <code>Create new branch...</code></li>
<li>Enter <code>feature/Your username</code></li>
<li>Click publish branch button on bottom left corner beside <code>feature/Your username</code></li>
<li>Click branch name on bottom left corner to switch branches</li>
</ol>

Congratulations! You have just learned how to setup github for collaboration. You are now able to collaborate with others in GitHub.

## Workflow

Update repository to the latest change

<ol>
<li>Switch to <code>feature/Your username</code> branch</li>
<li>Open command pallette<code>ctrl+shift+p</code></li>
<li>Type<code>git stash</code> and select <code>Git: Stash</code></li>
<li>Hit <code>enter</code> and select <code>Save All & Stash</code></li>
<li>Switch to <code>main</code> branch</li>
<li>Click synchronize button</li>
<li>Switch to <code>feature/Your username</code></li>
<li>Click synchronize button</li>
<li>Open command pallette<code>ctrl+shift+p</code></li>
<li>Type <code>git pop stash</code> and select <code>Git: Pop Stash...</code></li>
</ol>

Push your changes to main

<ol>
<li>Update repository to the latest change before push</li>
<li>Open source control from the left sidebar or <code>ctrl+shift+g</code></li>
<li>Hover <code>Changes</code> and click <code>+</code> to stage all changes</li>
<li>Type commit message above commit button (Do not skip this step!)<code></code></li>
<li>Click Commit button</li>
<li>Click Sync Changes button</li>
<li>(If you skip step 4, it will open a file. Close the file and continue from step 4.)</li>
</ol>

Congratulations! You are now a GitHub collaborator.
