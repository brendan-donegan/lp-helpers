# Launchpad Helpers

This project contains a set of helper scripts which I have found useful for everyday life as a developer hacking code on Launchpad with Bazaar. At the moment it contains these scripts.

## lp-file-bug

A script to file simple, uncluttered bugs from the command line. Just give it the name of the bug and the project and it will prompt you to enter a description. Use `lp-file-bug --help` for usage

## lp-propose-merge

A script to propose a merge in Launchpad with one command. It will prompt for a description of the merge but that's about it. Use `lp-propose-merge --help` to see other options.

## lp-recipe-build

Kicks off a recipe build for a branch in Launchpad which has an associated recipe. Specify the branch and it will pick the recipe to use (or show you your options if there is more than one). Use `lp-recipe-build --help` for more information.

## lp-clean-branches

Do some housekeeping of branches stored on disk. If they have been merged then delete them.
