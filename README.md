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
```

Yay! Your browser just opened and you're looking at https://github.com/me/appy/tree/mybranch/some/dir

## Caveats

You gotta be using https URLs in your `.git/config`. git:// URLs won't work.