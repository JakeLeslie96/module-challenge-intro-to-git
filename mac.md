## Research Questions 

Now that you are all set up, it's time to learn a little more about the tools of the trade. Edit this file and answer the following questions. You are going to need to start familiarizing yourself with the [GitHub docs](https://docs.github.com/en). Docs (short for documentation) are the instructions on how to use a languge or program. A large part of your job as a developer will be learning how to read and work with documentation. Please reference the GitHub docs when answering the questions below. If you cannot find what you are looking for in the docs, you can always start to practice your Google skills!

1. What is Git? GIT is a version control system, entirely client side. 
2. What is the difference between Git and GitHub? GitHub is a cloud based website where git can be shared amongst others. GitHub is essentially a Git Repository server 
3. Why do we create a branch? to make changes and tweak things before merging them into the code. Often to make sure it is working well with what others have been contributing.
4. What is the purpose of a Pull Request? To allow others to see that you have commited changes to whatever you are working on in your particular branch 
5. What is the command you can use to switch between branches? For example you are working on FIRSTNAME-LASTNAME branch and you want to switch back to main. Answer: git switch -c [name of branch]
6. Explain the difference between `git fetch`, `git merge` and `git pull`. What does each command do? 
fetch = downloading all history from remote branches 
pull = updatint curren branch with new updates from commits, it is the combination of fetch and merge. 
merge = combining current branch with that of the remote branches
7. What is a merge conflict? a merge conflict is when you have branches that that have competing commits, that is generally changes on the same lines, or when a file that has been edited by someone, is, in a seperate branch,  deleted by someone. 
8. How do you resolve a merge conflict? you must edit the files and lines in question and keep the code that you want introduced t the final merge. 
