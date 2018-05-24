# Mystery-Object-2
This project contains the second "mystery" object to test the use of Git for shared tracing projects.

## Invitation
Every member of the Reconstruct team is encouraged to clone this repository and work on a few sections according to the "Process" described below.

## Process

* Step 1: **Clone** this project (**git clone https://github.com/SynapseWeb/Mystery-Object-2.git**).

* Step 2: **Claim** some number of sections and **update** the "**Currently Claimed Sections**" below.

* Step 3: **Pull** from GitHub into your local directory (**git pull origin master**).

* Step 4: **Work** on your "Claimed Sections" in Reconstruct until they're done (or done for now).

* Step 5: **Commit** your changes locally (**git commit -a** or similar alternatives).

* Step 6: **Pull** again from GitHub and resolve any changes (in case anyone else has made changes).

* Step 7: **Push** your changes to GitHub (**git push origin master**).

* Step 8: **Unclaim** the sections you're done working on by removing them from your "**Currently Claimed Sections**".

* Step 9: **Go back** to Step 2 and "claim" some more section to work on.

## Currently Claimed Sections

* Sections 39-41: Bob

## Section Status (tables are easier to update than images!!)

| # / Status | # / Status | # / Status | # / Status | # / Status | # / Status | 
| ---------- | ---------- | ---------- | ---------- | ---------- | ---------- |
| 1 / Done  :heavy_check_mark: | 2 / Done :heavy_check_mark: | 3 / Done :heavy_check_mark: | 4 / Done :heavy_check_mark: | 5 / Done :heavy_check_mark: | 6 / Done :heavy_check_mark: |
| 7 / Done :heavy_check_mark: | 8 / Done :heavy_check_mark: | 9 / Done :heavy_check_mark: | 10 / Done :heavy_check_mark: | 11 / Done :heavy_check_mark: | 12 / Done :heavy_check_mark: |
| 13 / Done :heavy_check_mark: | 14 / Done :heavy_check_mark: | 15 / Done :heavy_check_mark: | 16 / Done :heavy_check_mark: | 17 / Done :heavy_check_mark: | 18 / Done :heavy_check_mark: |
| 19 / Done :heavy_check_mark: | 20 / Done :heavy_check_mark: | 21 / Done :heavy_check_mark: | 22 / Done :heavy_check_mark: | 23 / Done :heavy_check_mark: | 24 / Done :heavy_check_mark: |
| 25 / Done :heavy_check_mark: | 26 / Done :heavy_check_mark: | 27 / Done :heavy_check_mark: | 28 / Done :heavy_check_mark: | 29 / Done :heavy_check_mark: | 30 / Done :heavy_check_mark: |
| 31 / Done :heavy_check_mark: | 32 / Done :heavy_check_mark: | 33 / :red_circle:  | 34 / :red_circle:  | 35 / :red_circle:  | 36 / :red_circle:  |
| 37 / :red_circle:  | 38 / :red_circle:  | 39 / :arrows_clockwise:  | 40 / :arrows_clockwise:  | 41 / :arrows_clockwise:  |  |

## Discussion

This is our second experiment in building a collaborative tracing environment using GitHub. The first experiment was intentionally a "free for all" with no defined process to help highlight problem areas. The biggest problems we discovered were:

1. Two people working on the same section may have trouble merging.
2. Git will insert "edit markers" ("<<<<<" and ">>>>>") that must be resolved before pushing.
3. The series file is changed whenever the view is changed (almost every Reconstruct session).

The simplest solution for problem (1) is to simply not have multiple people working on the same section. The nice thing about having this README file as part of the Git repository is that it documents the "claiming" and "unclaiming" of sections in the same history with the updates to those sections. So there should be no question whether someone changed a section without claiming it first. The "claiming" commit should always happen before the changes, and it will be visible in the commit history.

The solution to problem (2) is likely more experience with Git. That should happen with time.

The solution to problem (3) is currently to ignore it (for now). Changes in the series (.ser) file can just be accepted by each person pulling from the repository. That means that previous settings and views will now be those of the last person to have committed. There are other alternatives, but this is easiest for now.


## "Mystery Object 2" so far (May 23rd, 2018):
![Animation](docs/Traces_2018_05_23.png?raw=true "Animation")

## All 41 sections (showing which have been completed):
![CompletedFrames](docs/All_Frames.png?raw=true "CompletedFrames")


Table Example:

| Command | Description |
| --- | --- |
| git status | List all new or modified files |
| git diff | Show file differences that haven't been staged |
