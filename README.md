# NCL sample presentation builder

This git repository contains a shell that can be used to build presentations using R.  It won't fit all circumstances perfectly, and you can make changes and issue a 
pull request for new features / changes.

The aim of this template is to allow people to automate the production of presentations for regular reporting. 


## To use this template, please use the following practises:

* Put any data files in the `data` folder.  This folder is explicitly named in the .gitignore file.  A further layer of security is that all xls, xlsx, csv and pdf files are also explicit ignored in the whole folder as well.  ___If you need to commit one of these files, you must use the `-f` (force) command in `commit`, but you must be sure there is no identifiable data.__
* Save any documentation in the `docs` file.  This does not mean you should avoid commenting your code, but if you have an operating procedure or supporting documents, add them to this folder.
* Please save all output: data, formatted tables, graphs etc. in the output folder.  This is also implicitly ignored by git, but you can use the `-f` (force) command in `commit` to add any you wish to publish to github.




This repository is dual licensed under the [Open Government v3]([https://www.nationalarchives.gov.uk/doc/open-government-licence/version/3/) & MIT. All code can outputs are subject to Crown Copyright.
