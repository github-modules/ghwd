# ghwd

A shell command to open a git URL in your browser that matches your
shell's current branch and working directory. Works for GitHub,
BitBucket, and GitLab repositories.

Runs on Mac, Linux, Cygwin, and Windows.

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

ghwd -b
# https://github.com/bozo/myapp/tree/mybranch
```

## Use it faster

A `g` alias is created automatically to save you three keystrokes:

```sh
g foo.js
```

## System Requirements

Requires the `bash` or `zsh` shell to run. Supports Mac, Linux, Cygwin and Windows by
searching for one of the following openers: `xdg-open`, `open`,`cygstart`,`start`.

## Providers

`ghwd` supports git repos from the following providers:

- [github.com](https://github.com) ssh, https and `git:` remotes
- [bitbucket.org](https://bitbucket.org) ssh and https remotes
- [gitlab.com](https://gitlab.com) ssh and https remotes

## See Also

If you are interested in further integration between your shell and Github,
check out the [hub](https://github.com/github/hub/) project. It adds a [git
browse](https://github.com/github/hub/#git-browse) command which works much
like this one, in addition to a number of other features.

## License

[ISC](http://opensource.org/licenses/ISC)

![octobiwan](octobiwan.jpg)
