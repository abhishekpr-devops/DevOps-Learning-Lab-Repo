# Mistakes Log

## Mistake: Incomplete terminal command
### What happened
I ran a long command to create folders and files, but the command ended with `&& \`.

### Why it happened
I added `&&` and line continuation `\` without giving the next command.

### How I fixed it
I cancelled the broken command using `Ctrl + C` and ran a clean corrected command.

### Lesson
Do not blindly paste commands. Check the last line before pressing Enter.

---

## Mistake: Weak verification
### What happened
I checked the project structure using `tree`, but I did not verify hidden files like `.gitignore`.

### Why it happened
I forgot that `tree` does not show hidden files by default.

### How I fixed it
I used `tree -a devops-learning-lab` to verify hidden files too.

### Lesson
Verification must be complete. Partial checking creates false confidence.

---

## Mistake: Rushing setup
### What happened
I focused on creating the structure fast instead of checking whether every required file was visible and correct.

### Why it happened
I was thinking about finishing, not validating.

### How I fixed it
I rechecked the structure carefully and compared it with the target layout.

### Lesson
Fast is useless if careless. Build, then verify.