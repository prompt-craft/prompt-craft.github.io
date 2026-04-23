# Prompt Craft

A lossy, inadequate translation into human language. Like whale song through human ears.

## Colophon

```bash
pandoc -f html -t markdown_strict -o README.md index.html && git symbolic-ref HEAD refs/heads/_ && rm .git/index && git add . && git commit -m "$(date)" && git branch -D main && git branch -M _ main && git reflog expire --expire=now --all && git gc --prune=all --aggressive && git push --force --set-upstream origin main
```