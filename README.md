# hello-gulp-js

A minimal gulp sample project that also uses npm and nodeenv.


## Building the Project

You create a [nodeenv](https://github.com/ekalinin/nodeenv),
install the project dependencides in it, and then run the build tool `gulp`.
Other wide-spread ones are `grunt` and `bower`.

```sh
git clone "https://github.com/jhermann/hello-gulp-js.git"
cd hello-gulp-js

test -e bin/npm || nodeenv --node=system --with-npm --force .
. bin/activate
test -d lib/node_modules/gulp || npm install -g gulp

npm install
gulp
```
