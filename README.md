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
```

## Use it faster

A `g` alias is created automatically to save you three keystrokes:

```sh
g foo.js
```

## System Requirements

Requires the `bash` shell to run. Supports Mac, Linux, Cygwin and Windows *by searching for one of the following openers, so other OSs may be supported as well: `xdg-open`, `open`,`cygstart`,`start`*.

## See Also

If you are interested in further integration between your shell and Github,
check out the [hub](https://github.com/github/hub/) project. It adds a [git
browse](https://github.com/github/hub/#git-browse) command which works much
like this one, in addition to a number of other features.

## License

[ISC](http://opensource.org/licenses/ISC)
