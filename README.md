my_git_commands
===============

A day in the life of me using git for Rails development.

I create a new rails directory / project so create the git repository:
```
git init
git add .
git commit -m 'created repository'
```

I want to create a branch, based on my master branch code, to do some development. The branch is called JSchanges:
```
git branch JSchanges
```
Go into that branch:
git checkout JSchanges

Make code changes, and when testing is good enough to commit:
```
git add .
git commit -m 'I removed some code from my JavaScript file'
```
Then go back to the master branch
```
git checkout master
```
Then merge the changes, if I'm happy with them, to the master branch
```
git merge JSchanges
```

Then repeat all over again, the next time I want to make changes.
