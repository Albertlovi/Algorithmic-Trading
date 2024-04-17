# git commands

## To make changes into the main branch

1. Make sure that you are up to date in the main branch:

```bash
git pull
```

2. Create a new sub branch:

```bash
git checkout -b name_of_the_sub_branch
```

or move to a sub branch

```bash
git checkout name_of_the_sub_branch
```

3. Set up stream with the main branch

```bash
git push --set-upstream origin subbranch
```

4. Make the desired changes in the sub branch

5. Add the changes:

```bash
git add .
```

6. Commit the changes

```bash
git commit -m "title_of_the_commit"
```

7. Push the commits in the main branch:

```bash
git push
```