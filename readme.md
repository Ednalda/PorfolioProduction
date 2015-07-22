##  Production Server - "productionSeverProfile":


    1. git add -A

    2. git commit -m 'message'

    3. git push productionServerProfile master


 ## Staging Server - "stagingPorfolio":

    1. git checkout master

    2. git pull stagingPorfolio master (Branch)

    3. check for conflits and resolve

 ## Need to commit

    4. git add -A

    5. git commit -am 'message'

    6. git pull origin master (github)

    7. git merge stagingPorfolio (Branch)

    8. git push stagingPorfolio master

 ## Test

 ## Deploy to productionServerProfile (LiveServer)

    9. git push origin master

    10. git push push productionServerProfile master


 
