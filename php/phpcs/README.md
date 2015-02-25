# PHP CodeSniffer Pre-Commit Hook

This pre-commit hook triggers a PHP CodeSniffer validation on the files you're about to commit, and only those files.

This code is based on [s0enke/git-hooks](https://github.com/s0enke/git-hooks) solution.

Original Author: Soenke Ruempler <soenke@ruempler.eu>

Original Website: http://github.com/s0enke/git-hooks

## Requirements

 * Bash
 * [PHP CodeSniffer](http://pear.php.net/package/PHP_CodeSniffer/redirected)


## Features

 * Check Coding style and forbid the commit if violations are found
 * Configuration file for Coding Standard, Path to PHPCS, Ignore List
 * Shows output in a 'less' pipe following the smart git principles


## Usage

Installation instructions:

 * Put the script "pre-commit" into your .git/hooks directory 
 * OR: add the script to your pre-commit "chain" (you probably know what to do then)
 * Put the Config file "config" into the same dir as the "pre-commit" script and
   edit it to your requirements
 * Ensure that the script is executable. 

You may use this hook with [Bladrak/Symfony2-coding-standard](https://github.com/Bladrak/Symfony2-coding-standard). You'll need to edit the ``PHPCS_CODING_STANDARD`` variable in the hook ``config`` file.