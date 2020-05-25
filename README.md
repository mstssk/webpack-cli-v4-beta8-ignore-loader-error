Reproduction code: webpack-cli v4-beta.8 ignoring loader's error.

Steps:
```sh
$ npm ci
$ npx webpack # Webpack returns exit code 0, but ts-loader raised error.
$ echo $? # 0
```
