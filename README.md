```console
$ npm install; npm test                                                                                                                                                                             master

added 5 packages, and audited 7 packages in 596ms

found 0 vulnerabilities

> tsbug@0.0.1 test
> npm test --workspaces


> tsbug@1.0.0 test
> tsc --noEmit

src/valid.ts:3:23 - error TS2339: Property 'isIP' does not exist on type 'typeof import("/Users/redacted/code/tmp2/tsbug/node_modules/@types/validator/index")'.

3 console.log(validator.isIP("12312"));
                        ~~~~


Found 1 error in src/valid.ts:3

npm ERR! Lifecycle script `test` failed with error:
npm ERR! Error: command failed
npm ERR!   in workspace: tsbug@1.0.0
npm ERR!   at location: /Users/redacted/code/tmp2/tsbug/apps/tsbug
```
