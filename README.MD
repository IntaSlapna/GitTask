#**Terminal commands for Task in Git**
     cd
     pwd
     mkdir gitTask
     cd gitTask
     git init
     git status
     touch README.MD
     vim README.MD
     vim README.MD
     cat README.MD
     git add README.MD
     git commit -m "Created README.MD file"
     git config --global user.name "Inta Slapna"
     git config --global user.email inta.slapna@accenture.com
     git commit --amend --reset-author
     git log
     git status
     git log --all --decorate --oneline --graph
     alias graph="git log --all --decorate --oneline --graph"
     graph
     git branch FeatureA
     git branch FeatureB
     git branch FeatureC
     git branch
     graph
     git checkout FeatureA
     graph
     git status
     vi S1
     git add S1 ; git commit -m "Made S1 in FeatureA"
     graph
     git checkout FeatureB
     git branch
     cat S1
     vi S2
     git status
     git add S2
     git commit -m "Made S2 in FeatureB"
     graph
     git checkout master
     git checkout FeatureC
     vi S3
     git add S3
     git commit -m "Made S3 in Featurec"
     graph
     git checkout master
     git diff master..FeatureA
     git branch FeatureD
     graph
     git branch FeatureD
     git checkout FeatureD
     git merge FeatureA
     ls -la
     git merge FeatureB
     ls -la
     git merge FeatureC
     ls -la
     git add S4
     git commit -m "Made S4 in FeatureD"
     git checkout master
     git merge FeatureD
     graph
     ls -la
     git status
     ssh-keygen
     cat /c/Users/inta.slapna/.ssh/id_rsa.pub
     git remote add origin git@github.com:IntaSlapna/GitTask.git
     git branch -M master
     git push -u origin master
   
