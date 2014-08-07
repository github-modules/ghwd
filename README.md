# ghwd

Open the GitHub URL that matches your shell's current branch and working directory

## Install it

```sh
npm install ghwd --global
```

## Use it

```sh
cd myapp
git checkout mybranch
cd some/dir

ghwd
# https://github.com/bozo/myapp/tree/mybranch/some/dir

ghwd foo.js
# https://github.com/bozo/myapp/tree/mybranch/some/dir/foo.js

git remote
# origin
# tomgco

ghwd tomgco
# https://github.com/tomgco/myapp/tree/mybranch/some/dir

ghwd tomgco foo.js
# https://github.com/tomgco/myapp/tree/mybranch/some/dir/foo.js
```

## Use it faster

A `g` alias is created automatically to save you three keystrokes:

```sh
g foo.js
```
