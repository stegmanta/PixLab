# Picture Lab

## Getting started

Fork and clone the [PixLab repo](http://github.com/mvhs-apcs/PixLab).

```
$ git fetch origin
$ git checkout a1
```

Read instructions for activity 1 in `Picture Lab Student Guide.pdf`.

`answers.md` has been provided for you to 
write the answers to any questions asked in the Student Guide.

Make commits to this branch as you complete the steps outlined in the activity.

## Submitting

Commit all local changes, then (replace # with the current activity number):
```
$ git push origin a#
```

## Switching to the next activity

For the first 5 activities (a1 through a5):

```
$ git checkout a#
```

The branches for activities 6-9 have not been created yet because their code builds on the previous exercises.

First, create a new branch
```
$ git branch a#
```

Then checkout it out
```
$ git checkout a#
```

Or, you can create and switch with one command with the `-b` shortcut
```
$ git checkout -b a#
```