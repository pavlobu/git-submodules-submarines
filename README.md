# git-submodules-submarines
following tutorial on git submodules from this video: https://youtu.be/eJrh5IjWSGM

# this is a public repo that will be a dependency of private repo 'surface'. Following the tutorial


to rename a submodule:
https://stackoverflow.com/questions/4526910/rename-a-git-submodule

```
I found following workflow working:

Update .gitmodules
mv oldpath newpath
git rm oldpath
git add newpath
git submodule sync
```