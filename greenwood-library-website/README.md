# Git Project Implementation

In this project, i am tasked with enhancing the website of "Greenwood Library Community". I wil be adding a "Book Reviews" section and also updating the "Event" page. 

To achieve this, I will be implementing some basic linux commands, cloning repository, staging, commiting and pushing changes. Also, I will be doing some pull request and merge. 

I will be simulating the roles of two contributors: "Morgan" who is focused on adding the Book Review and "Jamie" who is update the Event page.

I created files for the webpages for Greenwood Library website and included random content.

* home
* about_us
* events
* contact_us


These html files were created using `touch` command.

Content was added into each file using `echo` command with `>>`

![home](./img/1.home%20file.png)

![about_us](./img/2.about_us.png)

![events](./img/3.events.png)

![contact_us](./img/4.contact_us.png)


Files are ready to be staged. Here we use command `git add .` 

I made sure i was under the main branch


![git-status](./img/5.git-status.png)


## Staging

To stage my files and get them ready for commit, i used command `git add .`

This adds all the files to be committed.

![git-add](./img/6.git-add.png)


## Git Commit

I committed the files by using commmand `git commit -m` 

This takes the staged changes and records them in the repository's history with a message describing what was done. 


## Git push

After files had been commmitted, they were pushed to the remote repository using the command `git push`

![git-push](./img/8.git-push.png)


## Morgan's Work: Adding Book Reviews


To begin, i made sure i am in the folder containing the cloned Github repository on my local machine.

I execute git branch to check my current branch.

![git-branch](./img/9.git-branch.png)

Then i created a new branch for Morgan named "add-book-reviews". 
I did this by running commmand `git checkout -b add-book-reviews`

This command automatically switches to the newly created branch from the main branch.

![git-checkout-add-book-reviews](./img/10.add-book-reviews.png)

I created to file name book_reviews.html using the `touch` command

![book-revie](./img/11.book-review.png)

I staged Morgan's work by running `git add book_reviews.html`

![git-add-book-review](./img/12.git-add-book-reviews.png)

Git commit was done by runnning `git commmit -m book_reviews.html`
The `-m` in the command means message describing what was done.git com

![git-commit-book-reviews](./img/13.git-commit-book-review.png)

Morgan's Work was pushed to the remote repository by running the command `git push origin add-book-reviews`

![git-push-book-review](./img/14.git-push-add-book-review.png)


After a successful push, i did a pull request.

## Pull Request and Merge

A PuLL Request is a feature used in Github that allows you to notify team members about the changes you have pushed to a branch in a repository. 

A Merge of Pull Request is to merge all commits from the feature branch to the main branch in a merge commit. 

I did a successful Pull Request and Merge. 

![PR](./img/16.create-pull-request.png)

![](./img/15.git-pull-request.png)

![](./img/16.create-pull-request.png)

![](./img/18.MergenPull%20request.png)

![](./img/18.MergenPull%20request.png)

![](./img/19.confirmed-merge.png)


## Jamie's Work: Update Event Page

Step 1: I switched back to main branch.
i did this by running the code `git checkout main`

![git-main-switch](./img/21.switch-to-main.png)


Step 2: I did a git pull of Morgan's work to pull the latest changes.

![git-pull](./img/22.git-pull.png)


Step 3: Created new branch for Jamie's work

![update-event-branch](./img/23.update-event-branch.png)

Step 4: Event page was update with additional text and staged with `git add` 

![](./img/24.git-add-events.png)

Step 5: Git commit was done

![](./img/25.git-commit-update-event.png)

Step 5: Jamie's work was pushed to remote repo by doing git push

![git-push-update-event](./img/26.git-push-update-events.png)

Step 6: Pull Request and Merge was done on Jamie's work

![git-pr-merge](./img/28.git-PR.png)

![](./IMG/29.merge-PR.png)

![](./img/30.-merge-success.png)





