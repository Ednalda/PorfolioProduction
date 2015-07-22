# Deployment Plan:

##  Production Server - "productionSeverProfile":


 1. git add -A

 2. git commit -m 'message'

 3. git push productionSeverProfile master


 ## Staging Server - "stagingPorfolio":

 1.git checkout master

 2. git pull stagingPorfolio master

    1. check for conflits and resolve

 ## Need to commit

 1. git add -A

 2. git commit -am 'message'

 3. git pull origin master

 git merge staging

 ## Test

 1. git push stagingPorfolio master

 ## Tag release

 1. git tag -a   name -m 'feature name'

 2. git push staging --tags

 ## Promote to Staging

 1. git push staging master

 ## Test






   