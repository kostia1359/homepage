# Homepage
My very own personal website. Basically this is just a résumé
# Precommit 
You should use this for pre commit:
``` bash
#!C:/Program\ Files/Git/usr/bin/sh.exe
if workbox generateSW workbox-config.js ; then
  git add sw.*
  git add workbox-*
  exit 0
else
  echo "Cannot generate sw.js"
  echo "Aborting"
fi
```
# npm install
I should install [**serve**](https://github.com/zeit/serve) `npm install --global serve` for preview and [**workbox**](https://github.com/GoogleChrome/workbox) for caching `npm install --global workbox-cli`
