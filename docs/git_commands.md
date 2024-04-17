# git commands

## To make changes into the main branch

1. Make sure that you are up to date in the main branch:

```bash
git pull
```

2. Create a new branch:

```bash
git checkout -b name_of_the_branch
```

or move to an existing branch

```bash
git checkout name_of_the_branch
```

3. Set up stream with the main branch

```bash
git push --set-upstream origin name_of_the_branch
```

4. Make the desired changes in the branch

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

-----------------------------------------------------------------------------------------------------------------------------------------------------

## To rebase a branch with the main branch

1. Make sure that the main branch is up to date:

```bash
git pull
```

2. Move to the other branch and run:

```bash
git rebase main
```

3. Resolve the conflicts that might appear one by one and continue:

```bash
git rebase --continue
```

After this you should get the following message 'Successfully rebased and updated refs/heads/name_of_the_branch.'

4. Force push the branch to the main branch:

```bash
git push --force
```

-----------------------------------------------------------------------------------------------------------------------------------------------------

## General commands:

To delete a branch:

```bash
git branch -d name_of_the_branch
```