# devops-as-1
1st assignment of DevOps Training

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
