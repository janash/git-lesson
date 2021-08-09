# Git Lesson

This lesson covers the basics of using git for version control.

This lesson is for the first day of the MSSE bootcamp.

To make a commit ("version" or "checkpoint") of your files, follow this procedure:

1. Make changes to your project that you would like to keep.
1. Tell `git` you are ready to create a checkpoint of your files (using `git add`).
1. Create a checkpoint using `git commit -m "message about what you did"`

## Adding Features
Features should be developed on branches. To create and switch to a branch, use:

`git switch -c new_branch_name`

`-c` means "create".

To switch to an **existing branch**, use

`git switch branch_name` 