# SPARQL_PLAYGROUND
This repository should host preconstructed SPARQL endpoints serving graphs of the variation graph toolkit via virtuoso backend.

As the data is fairly large, this repository might require you to have [git lfs](https://git-lfs.github.com/) installed.

## Run a SPARQL Endpoint
- extract the desired endpoint.
- `cd` into the unextracted folder until you are in `..../expasy4j-spaql/`.

### Install Virtuoso
#### Archlinux 
- `yay -S virtuoso`
- `rm -rf virtuoso-t`
- `ln -s /usr/bin/virtuosod virtuoso-t`
#### Ubuntu 
[Installing Virtuoso with Ubuntu Packages](http://vos.openlinksw.com/owiki/wiki/VOS/VOSUbuntuNotes).
### Run Virtuoso
- start the server by `./run-tomcat.sh`.
- optional argument `-p 8080` or any other port you want the server to serve at.
