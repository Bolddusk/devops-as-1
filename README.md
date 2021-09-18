# devops-as-1
1st assignment of DevOps Training

## - Agile vs DevOps
In an agile approach, some planning and design is done upfront, but the development proceeds in small batches and involves close collaboration with stakeholders. Changes are incorporated continuously and a usable version of a product is released at the end of the sprint which is reviewed by the stakeholders for feedback.

The goal of DevOps is to help bring together developers who write application software and operations who run the software in production. Also, to build and maintain the infrastructure where it runs. 

In agile the development is divided into batches and when the software is tested and the bugs are fixed if any deployment is on done on the end of the sprint where as in devOps as soon as the code is tested and it is correct it is deployed.


## - What are the benefits of Cloud Computing
 - Cost : Cloud computing eliminates the expense of buying hardware, software & the on premisis setup.
 - Global Scale : One can increase/decrease the resources as per usage.
 - Performance : Multiple servers are runing worldwide which are regularly updated to the latest generation of fast and efficient computing hardware.
 - Speed : It allows to deploy our service on few clicks
 - Producitivity: All the work which we need to setup an on-premisis server isn't required at all.
 - Reliability : It makes data backup, disaster recovery, and business continuity easier and less expensive because data can be mirrored at multiple servers across the network.

## - Git vs GitHub
Git is a VCS technology which works on local computer whereas Github is a cloud base service which has so many additional features.

## - Stages of Git
Git has 4 stages 
  1- Working directory
      The directory in which we are currently working.
  2- Staging
      Staging area is place prior to the actual implementation of changes. Where we usually group the files for single change/update.
  3- Local Repository
      the place where changes have been saved to local repository(in our local computer).
  4- Remote Repository
      This repository is on the cloud or if we have the on premisis server. Changes are pushed to it.
      
## - 3 methods of git reset?
      There are 3 methods of git reset
        1- Mixed :  Remove the commit from local repo, and also remove changes from staging area. It is the default. (git reset --mixed HEAD^)
        2- Soft : Remove the commit from local repo, but keep the les in staging area. (git reset --soft HEAD^)
        3- Hard : Remove the commit from local repo, and staging area and even change the local files. (git reset --hard HEAD^)
          - HEAD^ means go 1 commit back
