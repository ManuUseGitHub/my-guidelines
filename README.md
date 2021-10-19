# Set an eslint formater
1. install eslint
```cmd
$ npm i eslint
```
2. initialize eslint
```cmd
$ eslint --initialize
```
3. chose these options:
   1. problems
   2. commonjs
   3. none
   4. Yes for `typescript`
   5. environment `node`
   6. `json` for format
   7. install dependecies : yes
4. replace the rules from `.eslintrc` with `rules.json`
5. fix issues