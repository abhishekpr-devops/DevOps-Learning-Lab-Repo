# Merge Conflicts

## What is a merge conflict
A merge conflict happens when two branches change the same part of a file and Git cannot merge them automatically.

## When it happens
- Same line changed in two branches
- One branch deletes a file while another edits it
- Same section is changed differently

## In IntelliJ
- Left side = one version
- Right side = another version
- Result = final version I want to keep

## What I learned
A conflict does not mean Git is broken. It means Git needs my decision.

## How to resolve
1. Open conflicted file
2. Read both versions carefully
3. Decide what final content should be
4. Save the correct result
5. Stage the file
6. Commit the merge

## My mistake before
I changed files without fully understanding what each side meant.

## Lesson
Do not panic during conflicts. Read, choose, save, stage, commit.