# opensurgbot pages

GitHub pages for opensurgbot.

## Deploy

1. Commit to the `gh-pages` branch
```bash

```
2. Push to remote repository
```bash

```
GitHub will deploy the updated page automatically.

git branch -D gh-pages
git checkout --orphan gh-pages
git --work-tree ./web/ add --all
git --work-tree ./web/ commit -m "gh-pages"
git push origin HEAD:gh-pages --force
git checkout -f master