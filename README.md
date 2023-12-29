# Djinni package for Scoop

On Windows, [scoop.sh](https://scoop.sh/) is probably the best option for package management of applications.

This is the djinni bucket for [scoop.sh](https://scoop.sh/).

Usage:

```bash
scoop bucket add xlcpp https://github.com/cross-language-cpp/djinni-bucket

scoop install xlcpp djinni-generator
```

Now you can run

```bash
djinni --version
```

The output should end with

```bash
djinni generator version 1.4.1
```

(or whatever the current version is)