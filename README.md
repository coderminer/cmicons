## Basic Usage

Collection Open source Svg icons and generate React Vue component,
now collect [jamicons](https://github.com/michaelampr/jam) [humbleicons](https://github.com/zraly/humbleicons)

[使用说明](http://coderminer.com/cmicons?from=npm)

## Vue

*Note that this library currently only supports Vue 3.*

First, install `cmicons-vue` from npm:

```sh
npm install cmicons-vue
```

Now each icon can be imported individually as a Vue component:

## [jam icon detail](icons_jam.md)
```vue
<template>
  <div>
    <SearchIcon style="color:red"/>
    <p>...</p>
  </div>
</template>

<script>
import { SearchIcon } from 'cmicons-vue/jam'

export default {
  components: { SearchIcon }
}
</script>
```

## [humble icon detail](icons_humble.md)

```vue
<template>
  <div>
    <SearchIcon style="color:red"/>
    <p>...</p>
  </div>
</template>

<script>
import { SearchIcon } from 'cmicons-vue/humble'

export default {
  components: { SearchIcon }
}
</script>
```

## React

First, install `cmicons-react` from npm:

```sh
npm install cmicons-react
```

Now each icon can be imported individually as a React component:

## [jam icon detail](icons_jam.md)

```js
import { SearchIcon } from 'cmicons-react/jam'

function MyComponent() {
  return (
    <div>
      <SearchIcon />
      <p>...</p>
    </div>
  )
}
```

## [humble icon detail](icons_humble.md)

```js
import { SearchIcon } from 'cmicons-react/humble'

function MyComponent() {
  return (
    <div>
      <SearchIcon />
      <p>...</p>
    </div>
  )
}
```

## License

This library is MIT licensed.