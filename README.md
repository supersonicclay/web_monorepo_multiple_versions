Tinkering with npm workspaces.


Demonstrates the following:

* Two different applications, one using a package in this same repository (app1) and one pulling that package from the npm registry (app2)
* Two different applications (app2 and app3) using two different versions of the same dependency pulled from the npm registry (lodash in this case)

```sh
npm i

$ cd packages/app1
$ node index.js
INTERNAL
$ cd ../app2
$ node index.js
4.17.21
$ cd ../app3
$ node index.js
3.10.1
$ cd ../..
```
