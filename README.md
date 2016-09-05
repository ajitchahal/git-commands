:one: **Git switch remote urls**  
Verfiy the current remote url:
```
git remote -v
```

Switch to new repository:
```
git remote set-url origin http://gitlab.fs24.local/fs24/expert-forum.git
```
or
```
git remote set-url origin https://git.rz.is/knoffhoff/expert-forum.git
```

Simply switch the remotes and git push, all the changes since last push will be pushed.


More at:

https://help.github.com/articles/changing-a-remote-s-url/

:two: **install gollum app for wiki**
https://github.com/gollum/gollum/wiki/Installation

:three: 
**Save git credentials**
```
git config --global credential.helper cache
```
