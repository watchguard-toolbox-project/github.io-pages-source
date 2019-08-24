
Sphinx setup for github pages 

Requires (package names on ubuntu 18):

* python3
* inotify-tools
* python3-sphinx
* python3-cloud-sptheme
* python3-recommonmark

Setup:

after cloning this repo, please clone also 
the documentation repo into docs:

git clone git@github.com:watchguard-toolbox-project/watchguard-toolbox-project.github.io docs

Workflow:
after changing the restructured text files (.rst) in source/
do a make to create actual files in docs/

then cd into docs directory and commit and push the changed html files in docs/
