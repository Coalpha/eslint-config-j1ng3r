# eslint-config-j1ng3r

An ESLint config made by [me](https://github.com/Coalpha) for [Marcus](https://github.com/j1ng3r).

Warnings are suggestions.
Errors should always be followed.
This repository is not published on npm (yet).

## Installation

Download [.eslintrc.js](.eslintrc.js)

Then stick it into whatever folder that your code is in

![](2019-03-28-23-57-46.png)

Open cmd or powershell and `npm i -D eslint`

![](2019-03-29-00-10-45.png)

Open Visual Studio Code and add the directory to the workspace

![](2019-03-29-00-13-02.png)


Make sure that "ESLint" by "Dirk Baeumer" or similar is installed

![](2019-03-29-00-01-25.png)

Does your code look like this? It's probably too clean.

![](2019-03-29-00-15-22.png)

Press `Ctrl+Shift+P` to bring up the command pallet. Type in `eslint fix` or similar

![](2019-03-29-00-14-28.png)

![](2019-03-29-00-16-02.png)

Well, that "helped".
Unfortunately there aren't any built in rules to disable spaces on infix operators like `=`

![](2019-03-29-00-18-00.png)

You'll have to delete the spaces yourself.
