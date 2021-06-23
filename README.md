# Patch fix for Bulma 0.9.2
## The issue
Latest version of sass has a breaking change  that it doesn't allow slashed as divination (more can be read [here](https://sass-lang.com/documentation/breaking-changes/slash-div)
`bulma` still makes use of this and throws a lot of warnings when developing locally.

## The patch fix
Created this fork and used [sass-migrator](https://sass-lang.com/documentation/cli/migrator) to fix the warnings.

I found the solution [here](https://github.com/jgthms/bulma/issues/3333#issuecomment-852385442)


# Fork of [Bulma](https://bulma.io)
