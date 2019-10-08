# IVR Project Timeline #

## Phone System Upgrades ##

### IVR Upgrade ###

  #### Project Items ####

* We determined that Phases 1a and 1b will be combined into essentially an IVR upgrade with a number of code changes.
* Mike Irwin will work with Jeff to get him access to the IVR systems and SVN.
* Jeff will re-acclimate to the system and maybe see if he can tell why AES 6 was difficult to remove.
* Fran will continue to work on IVR upgrade quotes.
* Mike Irwin is going to work with Marshall on the AES 7 H/A settings that were left over in the system and a plan to remove them.
        * Change host file delete non active IP address and shutdown the interface.
* Kenny and Josh will work on narrowing down short term code changes versus long term. They will then communicate these with Marshall, Jeff, and Mike I and develop a plan to test and implement the short term changes.
* Jeff, Marshall, and Mike I will work on locating all code and making sure we have a 100% copy of what is running in production stored in SVN.
* Determine if IVR can be upgraded prior to Core upgrade
* Gather IVR high priority requirements from CS
* Obtain quotes for phase 1b upgrades from C1 and SKC
* Troubleshoot to determine what brakes in the IVR when AES 6 is removed
* Review certs, usernames, passwords, etc
* Upgrade Nuance
* Upgrade and virtualize CBA
* Upgrade and virtualize MPP's
* Upgrade and virtualize VPMS (AEP)
* Upgrade Tomcat servers
    
  #### Make adjustments necessary to remove AES 6 ####
  
  * Fix cmvdn pointers
  * Reduce hard coding if it makes sense
  * Add additional code comments
  * Make AES 6 to 7 adjustments
    
  ##### Test the IVR without AES 6 in off hours in prod #####
  
  ##### Remove AES from Prod and implement code changes #####
  
### Core Phone System Upgrade ###

### Long Term Strategy ###

http://sharepoint2013.scriptpro.com:36573/colproj/IVR Upgrade/_layouts/15/start.aspx#/


