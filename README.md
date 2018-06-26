# steps to reproduce:
- npm install
- npm test

my return:
```
$ npm test

> glyphhanger-test@1.0.0 test /Users/danielbammer/git/glyphhanger-test
> glyphhanger foobar.html --json

(node:28761) UnhandledPromiseRejectionWarning: Error: ENOENT: no such file or directory, open '/Users/danielbammer/git/glyphhanger-test/node_modules/glyphhanger/node_modules/characterset/lib/characterset.js'
(node:28761) UnhandledPromiseRejectionWarning: Unhandled promise rejection. This error originated either by throwing inside of an async function without a catch block, or by rejecting a promise which was not handled with .catch(). (rejection id: 1)
(node:28761) [DEP0018] DeprecationWarning: Unhandled promise rejections are deprecated. In the future, promise rejections that are not handled will terminate the Node.js process with a non-zero exit code.
```
