# unplugin-start-template

unplugin start template

<details>
<summary>Vite</summary><br>

```ts
// vite.config.ts
import UnpluginStart from 'unplugin-start-template/vite'

export default defineConfig({
  plugins: [UnpluginStart()],
})
```

<br></details>

<details>
<summary>Rollup</summary><br>

```ts
// rollup.config.js
import UnpluginStart from 'unplugin-start-template/rollup'

export default {
  plugins: [UnpluginStart()],
}
```

<br></details>

<details>
<summary>esbuild</summary><br>

```ts
// esbuild.config.js
import { build } from 'esbuild'

build({
  plugins: [require('unplugin-start-template/esbuild')()],
})
```

<br></details>

<details>
<summary>Webpack</summary><br>

```ts
// webpack.config.js
module.exports = {
  /* ... */
  plugins: [require('unplugin-start-template/webpack')()],
}
```

<br></details>

<details>
<summary>Vue CLI</summary><br>

```ts
// vue.config.js
module.exports = {
  configureWebpack: {
    plugins: [require('unplugin-start-template/webpack')()],
  },
}
```

<br></details>

## License

[MIT](./LICENSE) License © 2022 [kriszu](https://github.com/wangsizhu0504)
