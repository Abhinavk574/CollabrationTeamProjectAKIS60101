# **INTRODUCTION TO GITFLOW**

## _What is **GITFLOW**?_ 

* GitFlow is a branching model for Git, created by **Vincent Driessen**.
* It was very well suited to collaboration and scaling the development, which help get attract alot attention.

## Key Benefits of **GITFLOW**

* Parallel Development
    * GitFlow makes parallel development very easily by isolating new development from finished work.
    * New development will be performed in **feature branches** such as non-emergency bug fixes and features.
    * Finally, when the developer is happy the code is ready to release, he/she can merge back into main body of code.
    * Note: if you are asked to switch from one task to another, you just need to commit your changes and then create a new feature for your new task. Furthermore, when the task is done, just simply checkout your original feature branch, and you can continue where you left off.
* Collaboration
    * Feature branch makes it easier for two or more developers to collaborate on the same feaure
    * Feature branch is a sandbox where the only changes are the changes necessary to get the new feature working. As a result, that makes it very easy to observe and follow what each collaborator is doing.
* Release Staging Area
    * Once new development is completed, it gets merged back to into **develop branch**, which is known as the staging area for all completed features that haven't yet released.
    * Hence, when the next release is branched off of **develop**, it will automatically contain all of the new stuff that has been finished.
* Support For Emergency Fixes
    * GitFLow supports **hotfix branched**, meaning branched made from a tagged release.
    * User can use these to make an emergency changes, safe in the knowledge that the hotfix will only contain your emergency fix
    * There is no risk that you will accidentally merge in new development at the same time.

   








