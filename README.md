## git bash or CLI command for GitHub Repository

**If your questions are there:**

   * [x] i need some terminal command with serially with small text note:

   * [x] I am using  git bash terminal.

   * [x] i am working on git master branch.
   * [x] i want make master to main branch.
   * [x] i need to push code this main branch.

   * [x] i need to create a new branch(name: newBranch1 ).
   * [x] i need to push code this new branch(newBranch1).

   * [x] again i need to create a new branch(name: newBranch2 )
   * [x] i need to push code this new branch(newBranch2)

   * [x] again i need to create a new branch(name: newBranch3 )
   * [x] i need to push code this new branch(newBranch3)

   * [x] and now i need go previous branch like(name: newBranch1 )
   * [x] and need to push code this branch(newBranch1)

   * [x] after that again need to go branch(name: newBranch3 )
   * [x] and continue code push code this branch(name: newBranch3 )




**Answer is here :**

```bash

# Change from "master" to "main" branch and push code
git branch -m master main
git push -u origin main

# Create and push code to "newBranch1"
git checkout -b newBranch1
git push -u origin newBranch1

# Create and push code to "newBranch2"
git checkout -b newBranch2
git push -u origin newBranch2

# Create and push code to "newBranch3"
git checkout -b newBranch3
git push -u origin newBranch3

# Switch back to "newBranch1" and push code
git checkout newBranch1
# Make changes and commits as needed
git push origin newBranch1

# Switch back to "newBranch3" and continue pushing code
git checkout newBranch3
# Make changes and commits as needed
git push origin newBranch3


```