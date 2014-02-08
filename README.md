# ghwd

Open the github URL that matches your shell's current branch and working directory

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
```

## Use it faster

```sh
alias g=ghwd
```