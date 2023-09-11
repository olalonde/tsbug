```console
$ npm install
$ npx tsc --noEmit
src/valid.ts:3:23 - error TS2339: Property 'isIP' does not exist on type 'typeof import("/Users/redacted/code/tmp2/tsbug/node_modules/@types/validator/index")'.

3 console.log(validator.isIP("12312"));
                        ~~~~


Found 1 error in src/valid.ts:3

```
