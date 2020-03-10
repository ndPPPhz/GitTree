# git-tree
![](https://img.shields.io/badge/node-green)

## Introduction
`git-tree` is a node script which prints the tree of all the active PRs and keeps update the depending ones pulling the state from the dependent PR.

<img src= "https://user-images.githubusercontent.com/6486741/76360387-cd1dcf00-6314-11ea-8d0e-7e0b362ecc05.gif">

---

## Usage

- Generate a valid token from https://github.com/settings/tokens

```bash
node git-tree.js [FLAG]
```

FLAG | Meaning
------------ | -------------
`--all` | Prints out the state of all the active PRs
`--token TOKEN` | Save a new token
`--path PATH` | Repository local path. Default `.`

---

## License

[![License](http://img.shields.io/:license-mit-blue.svg?style=flat-square)](http://badges.mit-license.org)

**[MIT license](http://opensource.org/licenses/mit-license.php)**
- Copyright 2020 © Annino De Petra
