>## This Project is presently Not Maintained
## If there is any interest in a transition of ownership, that would be ideal so that issues can be patched until dependent projects are updated.

>### Please see https://github.com/gaearon/react-hot-loader/issues/385#issuecomment-250941283 for a more comprehensive explanation 




### Babel preset for React HMR and Error Catching
[![Circle CI](https://circleci.com/gh/danmartinez101/babel-preset-react-hmre.svg?style=shield)](https://circleci.com/gh/danmartinez101/babel-preset-react-hmre)

This preset will configure Babel 6 for https://github.com/gaearon/react-transform-hmr and friends.

It is recommended that this preset only be configured for your development builds.

#### Install

```

npm install babel-preset-react-hmre --save-dev

```

#### Configure babel via .babelrc
```

{
  "presets": ["react", "es2015"],
  "env": {
    "development": {
      "presets": ["react-hmre"]
    }
  }
}

```
