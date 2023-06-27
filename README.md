# JS Digger

* fetch the list of most recently uploaded packages from https://www.npmjs.com/
* check if we have link to the VCS each project uses.
* If it is GitHub check if  in their GitHub repo there is a `.travis.yml` file.


This tool is similar to [PyDigger](https://pydigger.com/) but for NodeJS.
It monitors the packages as they are uploaded to [npmjs](https://www.npmjs.com/) and analyze them.
The first thing to check is which one of the packages are hosted on GitHub
and among them which ones have test and which don't.


Some links to explore

* https://www.edoardoscibona.com/exploring-the-npm-registry-api
* https://registry.npmjs.org/
* https://registry.npmjs.org/recent
* https://github.com/npms-io/npms-analyzer
* https://replicate.npmjs.com/_all_docs
* https://api.npmjs.org/downloads/range/${requestRange.from}:${requestRange.to}/${encodeURIComponent(name)};
* https://stackoverflow.com/questions/48251633/list-all-public-packages-in-the-npm-registry
