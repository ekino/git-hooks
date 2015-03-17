Commit Message Pre-Commit Hook
==============================

This pre-commit hook checks that the commit message matches a specified
pattern.

Requirements
------------

-   Bash

Features
--------

-   Check that the commit message matches specified RegEx (limited to
    the first line)

Usage
-----

Installation instructions:

-   Put the script "commit-msg" into your .git/hooks directory
-   OR: add the script to your commit-msg "chain" (you probably know
    what to do then)
-   Put the Config file "config" into the same dir as the "commit"
    script and edit it to your requirements (select the correct RegEx
    pattern)
-   Ensure that the script is executable.
