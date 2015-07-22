#h1 Deployment Plan:

##h2 Production Server - "productionSeverProfile":


 1. git add -A

 2. git commit -m 'message'

 3. git push productionSeverProfile master


 ##h2 Staging Server - "stagingPorfolio":

 1.git checkout master

 2. git pull stagingPorfolio master

    1. check for conflits and resolve

 ##h2 Need to commit

 1. git add -A

 2. git commit -am 'message'

 3. git pull origin master

 git merge staging

 ##h2 Test

 1. git push stagingPorfolio master

 ##h2 Tag release

 1. git tag -a   name -m 'feature name'

 2. git push staging --tags

 ##h2 Promote to Staging

 1. git push staging master

 ##h2 Test






   