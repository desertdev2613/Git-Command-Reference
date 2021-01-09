# Common Git Commands 

<img src="./images/git.png" style="text-align:center;">

 <h1 style="color:green; font-weight:bold;">⭐️ git clone</h1>
  <p>Git clone is a command for downloading and existing repository. This creates an identical copy of the latest version to your local computer.</p>

   <h1 style="color:green;font-weight:bold;">⭐️ git init</h1>
  <p>Creates an empty Git repositorylll. An initial branch without any commits will be created.</p>

  <h1 style="color:green;font-weight:bold;">⭐️ git add .</h1>
  <p>When we modify a file in our project these chagnes will happen locally, therefore we need to add them to our commit in order to push the changes to our repository. </p>

 <h1 style="color:green;font-weight:bold;">⭐️ git commit -m "message"</h1>
  <p>It commit is like setting a checkpoint in the development process. This allows us to go back to this moment in time if we need too.<br/><br/>
  
  Included in our commit we want to write a message explaining what we have developed or chagned in the source code.</p>

   <h1 style="color:green;font-weight:bold;">⭐️ git push</h1>
  <p>After committing your changes, you will want to "push" your changes to the remote server which Git will uploadfor you to your remote repository (GitHub).</p>

 <h1 style="color:green;font-weight:bold;">⭐️ git branch {branchName}</h1>
  <p>Branches are highly important. Branches create a safe space in a parallel world where you can work on the same project as another developer simultaneously. Creating branches helps to keep your main branch safe and in good working condition.<br/><br/>
  
  git branch nameOfNewBranch will allow you to create a new branch to safely work from.</p>

   <h1 style="color:green;font-weight:bold;">⭐️ git branch</h1>
  <p>Branches are highly important. Branches create a safe space in a parallel world where you can work on the same project as another developer simultaneously. Creating branches helps to keep your main branch safe and in good working condition.<br/><br/>
  
  The command git branch will allow you to see which branch you are currently working on.  </p>

  <h1 style="color:green;font-weight:bold;">⭐️ git checkout {branchName}</h1>
  <p>In order to work on a branch you will need to switch to it from your main branch. git checkout nameOfBranch will allow you to switch between branches.</p>

   <h1 style="color:green;font-weight:bold;">⭐️ git status</h1>
  <p>The git staus command gives all of the necessary information about the current branch.<br/><br/>
  💻 Is branch up to date?<br/>
  💻 Is there anything to commit or push?<br/>
  💻 Are files staged, unstagted or untracked?<br/>
  💻 Are there files that have been created, modified or delted?<br/>
  </p>

 <h1 style="color:green;font-weight:bold;">⭐️ git pull</h1>
  <p>Git pull allows us to receive updates from the remote repository.This command is a combination of git fetch and git merge which means that, when we use git pull, it gets the updates from remote repository (git fetch) and immediately applies the latest changes in your local (git merge).</p>

 <h1 style="color:green;font-weight:bold;">⭐️ git merge</h1>
  <p>Once everything on your branch is working and how you intend for it to be, the final step is to merge the branch with your main branch. Git merge will allow you to do this.<br/><br/>

  Git merge integrates your feature branch with all of it's commits into your main branch. You may have to resolve some merge conflicts but once they have been sorted through you will be able to safely merge your feature branch into your main. 
  </p>

