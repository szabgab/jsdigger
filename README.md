# JS Digger

* fetch the list of most recently uploaded packages from https://www.npmjs.com/
* check if we have link to the VCS each project uses.
* If it is GitHub check if  in their GitHub repo there is a `.travis.yml` file.


This tool is similar to [PyDigger](https://pydigger.com/) but for NodeJS.
It monitors the packages as they are uploaded to [npmjs](https://www.npmjs.com/) and analyze them.
The first thing to check is which one of the packages are hosted on GitHub
and among them which ones have test and which don't.

