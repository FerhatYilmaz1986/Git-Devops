## GITFLOW  
   
Git is a set of layers and each layer kind of has a function. The function is dependent on the layer but all you do with Git is you move files between these layers, and the layers provide error control, redundancy, and more things.
For example, you create a file in your repository, such as a Python file. These changes, that you've made to this file you've created are not tracked by Git, by default, you have to tell Git that you want to track this file. So you should tell Git to include the files in the next snapshot. If you've edited more files, you can also add them to the staging area, and eventually you end up with a staging area that has a few files, but changes are still not tracked until you commit them; you create a snapshot of the files. So what you do, is you commit the files to the local repository, and this creates a snapshot of them. Let’s say you create a simple application and you add it to the staging area, and you commit it, that saves that file in its current status. If you then add more code, you will add it again to the staging area, and commit it again, and the changes between version one and version two will be saved as a separate commit, and than as you do this more often, you may build up a history of versions of your file, where each version has some more code. This means that you can go back in time to a previous commit if you, for example, made a mistake, or you want to remove some code.  
  
## Git commands and terminology you should know :
  
Repository: Git repository is simply a file that you create in your computer and you want to initialize git in it  
  
**Clone**: This command gives us a copy of repository that we want to work on and collaborate  
  

 ![Git Clone](/image/clone.png)