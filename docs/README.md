# Overview
This repository contains an exam. The questions can be found within the [docs/exam/](./exam/) folder. You will also use this repository to submit your answers.


# Accept the Repository
You can find a Github Classroom invitation to this repository by click on the week number in the course website. You should be prompted with an invitation asking you to accept the assignment. Use a Github account created under your institutional email to accept the invitation. Once accepted, Github will fork the upstream repository (the instructor's repository) and create a downstream repository under your Github account.

Clone your downstream repository to your computer use:

```
git clone "name_of_the_downstream_repo" "name_of_the_local_folder"
```

This will generate a local repository on your computer. 

# Update the Repository

You can add additional files to the repository as needed. Stage and commit your changes use:

```
git add -A && git commit -m "YOUR message" && git push
```

This will update both the repository in your computer and in your Github account. You make any changes before the deadline passes.

Occasionally, the instructor might update the repository. You can sync with the upstream repository use:

```
git fetch upstream && git merge upstream/master
```

# Submit the Repository
Before you submit your repository for grading. Make sure the *\_\_REPORT\_\_.md* files are rendered correctly in your web browser, and all items are visible. Make a final commit to submit your work.
