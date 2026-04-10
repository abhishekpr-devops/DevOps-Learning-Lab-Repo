# Mistakes Log

## 2026-04-10

### Mistake 1: Wrong Git identity on first push
**What happened:**  
I pushed commits with the wrong Git email, so GitHub showed the wrong contributor account.

**Why it happened:**  
I did not verify `git config user.name` and `git config user.email` before first push.

**How I fixed it:**  
I corrected the Git identity, amended the commit author, and pushed corrected history.

**Lesson:**  
Always verify Git identity before first commit in a new repo.

---

### Mistake 2: Incomplete terminal command
**What happened:**  
I ran a command ending with `&& \` and Bash waited for more input.

**Why it happened:**  
I pasted a multi-line command without checking the last line.

**How I fixed it:**  
Cancelled with `Ctrl + C` and reran a corrected command.

**Lesson:**  
Check the full command before pressing Enter.

---

### Mistake 3: Non-fast-forward push rejection
**What happened:**  
Git rejected my push because local `main` was behind `origin/main`.

**Why it happened:**  
I tried to push before syncing remote changes.

**How I fixed it:**  
I pulled the latest changes, resolved the issue, then pushed again.

**Lesson:**  
If push is rejected, sync first. Do not blindly retry push.