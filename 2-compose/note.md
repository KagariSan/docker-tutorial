# Question 1
Let say you need postgree and redis for your application to start in local. How you gonna do?

## Old way
Spend a day intall postgree, db management tools, redis...
And spend time later if you need to reconfiguration something.

## Docker way
Let just make a docker-compose file and fired it up.
Everything will be up and ready in less than 30 minutes.
If you no longer needed it and need to stop in temporary then just one command, it's stop and return value resource of your computer back (CPU, RAM) and you can start another container to continue your jounery to the DevOps.

# Question 2
Let say you have your enviroment already. Now it's time to upgrade the DB to newer version. How you gonna do?

## Old way
Spend a day intall another version of database. Run both and try if it's working ok. If it's good then remove the old one and reconfiguration the new one to be default.

## Docker way
Let just make another docker-compose file and fired it up.
Everything will be up and ready in less than 30 minutes.
If you no longer needed it and need to stop in temporary then just one command, it's stop and return value resource of your computer back (CPU, RAM) and you can start another container to continue your jounery to the DevOps.