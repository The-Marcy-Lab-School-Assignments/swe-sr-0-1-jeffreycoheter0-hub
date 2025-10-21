# Technical Writing Assignment

For guidance on setting up and submitting this assignment, refer to the Marcy lab School Docs How-To guide for [Working with Short Response and Coding Assignments](https://marcylabschool.gitbook.io/marcy-lab-school-docs/how-tos/working-with-assignments#how-to-work-on-assignments).

## Prompt 1

A good technical explanation often uses a metaphor to help others understand a complex concept. Choose a metaphor to represent a Git commit. 

In a few brief paragraphs, use your chosen metaphor to explain:
* What a commit is
* How a commit is created (include the command-line syntax)
* Why commits are useful in version control.
* Why it is important to write descriptive clear messages in team settings.

### Response 1
* A `commit` is like adding a bookmark to a book. You always jot it down in the book to remind yourself where you left off. And could also be a way to bookmark notes. For example, when you find something interesting in the book, you can leave a note, adding a comment to explain why you bookmarked it.

* The `commit` command-line syntax is usually:
```json
 git commit -m ''
 ``` 
 The `commit` records all changes made to that file. When staging something you typical use:
 ``` json
 git add 
 ```
 Stages basically means dressing up the code, getting it ready to go out. The `git add` prepares the file for a `commit`. Meaning it records the changes with a comment in the data history.

* `Commits` are super reliable and understandable. You can always review your `commits` to understand why you made a change or when you completed a task. Basically, documenting your code. When working with a team, you will usually `branch` out to different `branches` in a file so each person can make their own changes while not affecting the code in the `main` branch. `Committing` enables contributors to explain their own changes without affecting the `main` file code. When they commit, you can view their comments explaining why or what changes they made, making it easy to identify changes to `merge` into the main file. 

* Going back to the previous answer, writing descriptive clear messages makes it easier for the team to identify the changes they made in their personal branch file. By reading each members changes, you can then collectively decide if it is worth `mergeing` with the `main` file. It's easy to keep track of just so their isn't any miscommunication. 