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
import { AlarmClockIcon } from 'cmicons-react/jam'

function MyComponent() {
  return (
    <div>
      <AlarmClockIcon />
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
    <AlarmClockIcon style="color:red"/>
    <p>...</p>
  </div>
</template>

<script>
import { AlarmClockIcon } from 'cmicons-vue/jam'

export default {
  components: { AlarmClockIcon }
}
</script>
```

## License

This library is MIT licensed.

Inspired by [Tailwind Heroicons](https://github.com/tailwindlabs/heroicons)