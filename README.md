# New Developer Onboarding

v0.0.3 [digital platform product engineering]

## Welcome to First Utility Digital Platform

During this first week, to get you accustomed to our tech stack, people and processes, you will be building an app!

As well as learning how we build apps, you will need to talk to people! If you get stuck ask somebody (if they don't look _really_ busy!) or in a Slack channel!

### Checklist

* Laptop
* Your Code IDE/Editor of choice
* NVM (or 'n') Node 6, Node 8 and NPM installed
* Access to [Artifactory](http://build-repo-dc2.prod.impello.co.uk:8081/artifactory/webapp/#/artifacts/browse/tree/General/npm-virtual)
* A `~/.npmrc` file with `registry = "http://build-repo-dc2.prod.impello.co.uk:8081/artifactory/api/npm/npm-virtual"` added
* GIT client or CLI
* You have set up your SSH keys ([see here](http://knowledge.impello.co.uk/confluence/display/DataWiki/Getting+ssh+to+work+with+Bitbucket+or+Stash)) in a `~/.ssh` directory
* Access to our internal [BitBucket](https://git.impello.co.uk/dashboard)
* [Slack](https://firstutilityengineers.slack.com) is installed and you are invited to a channel
* You have [email](https://mail.google.com/mail) access
* You have read the [Code Standards](https://docs.google.com/document/d/1n6UaAPVINDuJ39LJJE1Wz5NKipSJSJA6XFkTsNhPvvc/edit?usp=sharing) document
* You can access [LeanKit](https://first-utility.leankit.com/)

When you have completed the above checklist you will be ready to start creating your app!

The project you will build is a 'Question and Answer' app which will adhere to the following:

* Will be built from the [Next.js](https://nextjs.org/) project
* Will reside in a repo in **YOUR** personal BitBucket (Tip: Click on 'Manage Account' in the user menu)
* Will adhere to our **Code Standards**
* Will go through our PR process
* Will be discussed in our daily standup
* Will use the supplied **questions.json** file
* **You will supply the answers!**
* Can be as pretty as you like... :)

## Our Lean Kanban process

We use a [Lean Kanban](https://leankit.com/learn/lean/lean-kanban/) process for building our apps. Don't worry about taking all the following information in, you'll learn it as you do it daily.

Complete the following steps:

* Find the _on-boarding_ ticket in the Backlog on LeanKit
* Move to to _In Progress_
* Click into the ticket and find the _Tasks_
* Create a task for yourself to complete (we use these to break the larger ticket into smaller dev tasks)
* Move the task at the top left into the _Doing_ column
* Make a note of the **_OLW-_** number on the ticket
* Create a branch from your Master in GIT with the following format: \*feature/OLW-**\*\*\***-brief-description-of-task\*
* Write code & tests to complete the task in your preferred style (TDD/PDD)
* Create a PR when the task is **DONE**
* Move the sub-task out of the main ticket (make it into a card) and move it to the _Code Review_ column
* Ask team mates to review your PR in a slack channel
* After a successful review, merge the branch to Master
* Move the ticket to the UAT column
* Add a comment to the ticket with the required **_Test Steps_**
* Ask a team member to _test_ the ticket (remember to supply the built app URL in the test steps above)
* (In a _real app_ situation you would now release it to production, we won't do this here)
* When the ticket is successfully tested move the ticket to the _Recently Completed_ column
* **_Then, and only then, may you pick up another task_**

## The Q & A App Specification

The app will have the following spec:

* Mobile dimensions on phones AND desktop
* A snazzy name!
* A Landing page with instructions and App name
* 'Next >' buttons
* Question pages with 3 multiple choice answers
* Validation to make sure a question is selected
* A final 'Score' page
* A 'Start over' button

If you have _ANY_ questions, ask your team on Slack. Everyone will be glad to help.

### GET BUILDING!
