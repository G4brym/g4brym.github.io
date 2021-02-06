# g4brym.github.io
This is my personal portfolio
[Check it our here](https://g4brym.ovh)


## Git flow
### Setup
```bash
rm -rf public
echo "public/" >> .gitignore  # Already run
git worktree add public gh-pages
```

### Making changes
```bash
hugo
cd public
git add --all
git commit -m "$(git log '--format=format:%H' master -1)"
git push origin gh-pages --force
cd ..
```
