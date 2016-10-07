# Ionic 2 beta 11 blank starter


## What is this?
This is a copy of the blank starter project of ionic 2, compatible with ionic 2 beta 11 framework version.


## Why do I need this?
After updating to Ionic 2 RC0, some changes have been made in the structure of official ionic-blank-starter, that breaks compatibility with previous versions, so if you want to create an empty ionic project using beta11 like this: `ionic start --v2 myProject blank`, ionic will create a project based on an incompatible template, and when running `ionic serve`, you'll find the error `Error: ENOENT: no such file or directory, open '.../myProject/www/index.html'`.

This project is the solution to that problem.


## How to install

1. `git clone https://github.com/kaikcreator/ionic2-beta11-blank-starter myProject`
2. `cd myProject`
3. `npm install`

After this, you can work as usual, with `ionic serve` and all that stuff.

If you want to use it as a base of your own project repository, remember to remove the .git project to start from zero.


