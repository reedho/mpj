Webpack

TLDR; 

```
mkdir workdir
cd workdir
npm init -y
yarn add -D webpack webpack-cli
npx webpack
```

Per Webpack 4, `webpack` cli command bisa tanpa config file sama sekali. 

Default input (entry) adalah `src/index.js`.

Default output adalah `dist/main.js`

Default mode adalah 'production'. 

Default nama file config adalah `webpack.config.js`.

Contoh minimal file config:

```
module.exports = {
  entry: './src/index.js',
  output: { path: '/tmp/dist2', filename: 'result.js' }
}
```

Note that `output.path` harus absolute path. 

