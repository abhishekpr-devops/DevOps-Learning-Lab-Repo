# Mistakes and Lessons Learned

## Mistake 1: Pasting long heredoc commands incorrectly

### What happened
While updating README.md, incorrect text was pasted into the file.

### Lesson learned
For longer Markdown edits, use nano or a code editor instead of pasting long terminal heredoc blocks.

### Better approach
Use:

```bash
nano README.md
