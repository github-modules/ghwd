# ghwd

A simple command to open a GitHub URL in your browser that matches your shell's current branch and working directory

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

## License

[ISC](http://opensource.org/licenses/ISC)
