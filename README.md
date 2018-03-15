*This repository was created with the sole purpose of listing common debugging steps for later reference.*

---

## Problem:

Volumes do not show content/are empty

## Solution #1

1. Restart docker service
2. Restart container(s) in question
3. Validate the problem has been resolved
4. If the problem persists, a fresh build may be required to the container(s) in question.

---

## Problem:

Volumes only show a single folder or are empty in general

## Solution #1

*This solution is strictly related to changing the password of the user account on the host PC.*

1. Stop all containers
2. Right click on docker icon
3. Click `settings`
4. Click `Shared Drives`
5. Make note of the shared drives on your machine (you will need to reshare them)
6. Click `Reset credentials...`
7. Fill out the user form prompt by inserting your password and submit the prompt
8. Reshare the drives you listed in step 5
9. If the problem persists, a fresh build may be required to the container(s) in question.