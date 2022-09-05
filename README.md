## Basic Usage

Collection Open source Svg icons and generate React Vue component,
now collect [jamicons](https://github.com/michaelampr/jam)


## React

First, install `cmicons-react` from npm:

```sh
npm install cmicons-react
```

Now each icon can be imported individually as a React component:

```js
import { ActivityIcon } from 'cmicons-react/jam'

function MyComponent() {
  return (
    <div>
      <ActivityIcon />
      <p>...</p>
    </div>
  )
}
```

## Vue

*Note that this library currently only supports Vue 3.*

First, install `cmicons-vue` from npm:

```sh
npm install cmicons-vue
```

Now each icon can be imported individually as a Vue component:

```vue
<template>
  <div>
    <BeakerIcon class="h-6 w-6 text-blue-500"/>
    <p>...</p>
  </div>
</template>

<script>
import { ActivityIcon } from 'cmicons-vue/jam'

export default {
  components: { ActivityIcon }
}
</script>
```

## License

This library is MIT licensed.
