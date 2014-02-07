# ghwd

Open the github URL that matches your shell's current branch and working directory

## Install it

```
npm install ghwd --global
```

## Use it

```
cd myapp
git checkout mybranch
cd some/dir

ghwd
# https://github.com/bozo/myapp/tree/mybranch/some/dir

ghwd foo.js
# https://github.com/bozo/myapp/tree/mybranch/some/dir/foo.js
```
