# CS 3560 - Homework 3 - Git

A class repository for homework in CS3560. For the detail of the
assignment, please refer to the entry on Blackboard.

## Tips and Tricks

### `status` is too long

I found myself too lazy to type `git status`, so I have alias configured
so I can type `git st` for `git status`.

`git config --global alias.st status`

### Any pretty graph on a terminal?

![Pretty Git Log](.github/gitlgo.jpg?raw=true "Pretty Git Log")

Run the following command to get a graph like the one above.

`git log --graph --all --decorate --oneline`

Again alias can also be used, I usually map this one to `git lgo` for git log oneline.

`git config --global alias.lgo "log --graph --all --decorate --oneline"`

This trick is taken from [Linux.conf.au 2013 - Git For Ages 4 And Up](https://www.youtube.com/watch?v=1ffBJ4sVUb4)

