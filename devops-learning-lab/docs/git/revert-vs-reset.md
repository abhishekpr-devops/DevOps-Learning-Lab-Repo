# Revert vs Reset

## Revert
`git revert` creates a new commit that undoes an earlier commit.

### Why it is safe
It keeps project history clear and does not remove old commits.

## Reset
`git reset` moves branch history backward.

### Why it is risky
It can remove commits from normal history and cause confusion if used carelessly.

## Main difference
- Revert = undo by adding new history
- Reset = move history backward

## When to use revert
- Shared branch
- Public history
- Safe undo needed

## When to be careful with reset
- On main branch
- After pushing commits
- When working with others

## My rule
If I want safe undo, use revert first. Use reset only when I clearly understand the effect.