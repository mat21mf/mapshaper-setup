# Setup mapshaper

## Node.js

## Add node.js to bashrc

```console
echo ""                                                            >> ~/.bashrc
echo "## nodejs"                                                   >> ~/.bashrc
echo "if [[ ! -d ~/.npm-global ]] ; then mkdir ~/.npm-global ; fi" >> ~/.bashrc
echo "export NPM_CONFIG_PREFIX=~/.npm-global"                      >> ~/.bashrc
echo "export PATH=\"$PATH:/home/$USER/.npm-global/bin\""           >> ~/.bashrc
source ~/.bashrc
```

## mapshaper

```console
npm install -g mapshaper
```
