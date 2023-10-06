## git bash command GitHub

**if your question is that**

i need some terminal command with serially with small text note:

I am using  git bash terminal.

i am working on git master branch.
i want make master to main branch.
i need to push code this main branch.

i need to create a new branch(name: newBranch1 ).
i need to push code this new branch(newBranch1).

again i need to create a new branch(name: newBranch2 )
i need to push code this new branch(newBranch2)

again i need to create a new branch(name: newBranch3 )
i need to push code this new branch(newBranch3)

and now i need go previous branch like(name: newBranch1 )
and need to push code this branch(newBranch1)

after that again need to go branch(name: newBranch3 )
and continue code push code this branch(name: newBranch3 )




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