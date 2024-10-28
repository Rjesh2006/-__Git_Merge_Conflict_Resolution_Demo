# 🚀 Git Merge Conflict Resolution Demo

This repository showcases an in-depth journey through the process of **Git merge conflict resolution**. Below, you'll find a step-by-step guide, sample commands, and explanations to make handling merge conflicts straightforward. 

## Overview

**🎯 Tackling Git Merge Conflicts Head-On! 🎯**

As part of this project, I dove into **Git** and practiced managing merge conflicts across branches. The steps below illustrate each phase of creating, encountering, and resolving conflicts.

### Project Goals

- Demonstrate branching, merging, and conflict resolution.
- Document key Git commands.
- Provide a reference for future conflict management.

## Steps Walkthrough

1. **Initialize a New Repository**  
   Started by initializing a local Git repository with:
   ```bash
   git init

Create and Modify Branches
Created two branches, featureA and featureB, to simulate collaboration:

bash
git checkout -b featureA
# Made changes and committed them in featureA
```bash
git checkout -b featureB
```
# Made different changes in the same file and committed them in featureB

3. Simulate a Merge Conflict
Made conflicting edits to conflict.txt from both branches to trigger a conflict on merging.

4. Encounter and Resolve the Conflict
After merging branches, Git flagged the conflict. I manually resolved it by editing the conflict markers:
![image](https://github.com/user-attachments/assets/b5247ba4-a30f-4eb1-9ced-026a9606dbf3)


5.Commit the Resolved Changes
Once resolved, the changes were added to the staging area and committed:

```bash
git add conflict.txt
git commit -m "Resolved merge conflict"
```



## Git Commands Reference

**Initialize Repo**
- git init

**Create Branch**
- git checkout -b branch_name

**Stage Changes**
- git add .

**Commit Changes**
- git commit -m "message"

**Merge Branch**
- git merge branch_name

# Resolve Conflicts
 **Manually edit and save the conflicting files**

**Push to Remote**
- git push origin branch_name

## Finally!- 👀 Check out the project visuals below for a better understanding of the Git merge conflict resolution process!
 -  ![Screenshot 2024-10-27 231352](https://github.com/user-attachments/assets/0f3311e0-2920-41a9-ae40-c40534fe6265)
  
 [And CLICK here(DOWNLOAD THE RAW FILE TO WATCH THE VIDEO ) is the vidoe for the entire process of of the handling of conflicts here ](https://github.com/Rjesh2006/-__Git_Merge_Conflict_Resolution_Demo/blob/main/git-bash-conflict-s-handling_bg.mp4)

## Lessons Learned
-  Branching: Useful for working independently on features.
-   Merging: Combines branch changes into the main branch.
-   Conflict Resolution: Essential for effective collaboration in version control.



## Conclusion
- **This exercise was an excellent introduction to understanding and resolving Git merge conflicts. Feel free to explore the steps and commands in this repository to strengthen your Git skills! 🌟**
