# Common Git Commands 

<img src="./images/git.png" style="text-align:center;">

<dl>
 <dt style="color:green; font-weight:bold;">⭐️ git clone</dt>
  <dd>Git clone is a command for downloading and existing repository. This creates an identical copy of the latest version to your local computer.</dd>

   <dt style="color:green;font-weight:bold;">⭐️ git init</dt>
  <dd>Creates an empty Git repositorylll. An initial branch without any commits will be created.</dd>

  <dt style="color:green;font-weight:bold;">⭐️ git add .</dt>
  <dd>When we modify a file in our project these chagnes will happen locally, therefore we need to add them to our commit in order to push the changes to our repository. </dd>

 <dt style="color:green;font-weight:bold;">⭐️ git commit -m "message"</dt>
  <dd>It commit is like setting a checkpoint in the development process. This allows us to go back to this moment in time if we need too.<br/><br/>
  
  Included in our commit we want to write a message explaining what we have developed or chagned in the source code.</dd>

   <dt style="color:green;font-weight:bold;">⭐️ git push</dt>
  <dd>After committing your changes, you will want to "push" your changes to the remote server which Git will uploadfor you to your remote repository (GitHub).</dd>

 <dt style="color:green;font-weight:bold;">⭐️ git branch {branchName}</dt>
  <dd>Branches are highly important. Branches create a safe space in a parallel world where you can work on the same project as another developer simultaneously. Creating branches helps to keep your main branch safe and in good working condition.<br/><br/>
  
  git branch nameOfNewBranch will allow you to create a new branch to safely work from.</dd>

   <dt style="color:green;font-weight:bold;">⭐️ git branch</dt>
  <dd>Branches are highly important. Branches create a safe space in a parallel world where you can work on the same project as another developer simultaneously. Creating branches helps to keep your main branch safe and in good working condition.<br/><br/>
  
  The command git branch will allow you to see which branch you are currently working on.  </dd>

  <dt style="color:green;font-weight:bold;">⭐️ git checkout {branchName}</dt>
  <dd>In order to work on a branch you will need to switch to it from your main branch. git checkout nameOfBranch will allow you to switch between branches.</dd>

   <dt style="color:green;font-weight:bold;">⭐️ git status</dt>
  <dd>The git staus command gives all of the necessary information about the current branch.<br/><br/>
  💻 Is branch up to date?<br/>
  💻 Is there anything to commit or push?<br/>
  💻 Are files staged, unstagted or untracked?<br/>
  💻 Are there files that have been created, modified or delted?<br/>
  </dd>

 <dt style="color:green;font-weight:bold;">⭐️ git pull</dt>
  <dd>Git pull allows us to receive updates from the remote repository.This command is a combination of git fetch and git merge which means that, when we use git pull, it gets the updates from remote repository (git fetch) and immediately applies the latest changes in your local (git merge).</dd>

 <dt style="color:green;font-weight:bold;">⭐️ git merge</dt>
  <dd>Once everything on your branch is working and how you intend for it to be, the final step is to merge the branch with your main branch. Git merge will allow you to do this.<br/><br/>

  Git merge integrates your feature branch with all of it's commits into your main branch. You may have to resolve some merge conflicts but once they have been sorted through you will be able to safely merge your feature branch into your main. 
  </dd>

</dl>