# Mystery-Object-2
This project contains the second "mystery" object to test the use of Git for shared tracing projects.

## Invitation
Every member of the Reconstruct team is encouraged to clone this repository and work on a few sections according to the "Process" described below.

## Process

Step 1. Clone this project.

Step 2. Always start by "claiming" some number of sections and update the "Claimed Sections" below.

Step 3. Pull from GitHub into your local directory (git pull origin master).

Step 4. Use Reconstruct to work on your "Claimed Sections" until they're done (or done for now).

Step 5. Pull again from GitHub and resolve any changes.

Step 6. Push to GitHub (git push origin master).

Step 7. Unclaim any sections that you're done working on.

Step 8. Go back to Step 2 and "claim" some more section to work on.

## Claimed Sections

Sections 1-2: Bob

## Discussion

This is our second experiment in building a collaborative tracing environment using GitHub. The first experiment was intentionally a "free for all" with no defined process to help highlight problem areas. The biggest problems we discovered were:

1. Two people working on the same section may have trouble merging.
2. Git will insert "edit markers" ("<<<<<" and ">>>>>") that must be resolved before pushing.
3. The series file is changed whenever the view is changed (almost every Reconstruct session).

The simplest resolution for problem (1) is to simply not have multiple people working on the same section. The nice thing about having this README file as part of the Git repository is that it documents the "claiming" and "unclaiming" of sections in the same history with the updates to those sections. So there should be no question whether someone changed a section without claiming it first. The "claiming" commit should always happen before the changes, and it will be visible in the commit history.

The solution to problem 2 is likely more experience with Git. That should happen with time.

The solution to problem 3 is currently to ignore it (for now). Changes in the series (.ser) file can just be accepted by each person pulling from the repository. That means that previous settings and views will now be those of the last person to have committed. There are other alternatives, but this is easiest for now.


## "Mystery Object 2" so far (May 22nd, 2018) with no sections completed:

## All 41 sections (showing which have been completed):
![CompletedFrames](docs/All_Frames.png?raw=true "CompletedFrames")
