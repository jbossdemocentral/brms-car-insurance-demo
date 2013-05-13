# This is the directory where you would normally find the projects source code.

===

This project is built on the source for the "Red Hat Middleware 6 Products Demo". 

PLEAE NOTE - This project is a sandbox for ideas and test code and is not meant for production environments.
             All of the example will require Red Hat Enterprise Versions of JBoss Application Server and the BRMS (rules)   
             Platform. see https://access.redhat.com/downloads to sign up for an evaluation. 

You can obtain the project code (and the rest of the demos as they evolve) at:

https://github.com/RedHatEMEA/rh6pd

Below you can play with the project yourself, but the pre-built code that is used can be found in the support directory.

#Description#

Welcome to the JBoss Middleware six products demonstration suite. If your new to JBoss middleware this suite of simple demos will allow you to get up and running with six of the most popular JBoss products very quickly.

The  car insurance quote is implemented with JBoss Business Rules Management System (BRMS). This version of BRMS also includes a powerful embeddable Business Process Management system which is used to control the business process .


#Build Information#

To build the project:

  first clone from our V0.1.0 release tag to get the last working version of the car insurance demo.

        create a new directory
        cd into that directory 
        	git init 
        	git remote add origin https://github.com/RedHatEMEA/rh6pd
        	git fetch
        	git checkout tags/v0.1.0
        This will create a completely seperate instance at version 0.1.0 for testing.
        You will not be able to commit any changes to the master branch from here but 
        will give you a good view of the project

## zip ##
  maven install - will create a zip file in the rh6pd/rh6pd-packages target directory

