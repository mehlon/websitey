# websitey
statically generated website with 9base, on netlify

Netlify build command:
```export SITE=`pwd`/site PLAN9=`pwd`/usr/lib/plan9 && mkdir -p $SITE  && ./usr/lib/plan9/bin/fortune | tee $SITE/index.html```
