# Vue Brace

Code editor powered by Vue 2 and browserify Ace (Brace)

Fork of [vue-bulma-brace](https://github.com/vue-bulma/brace/)

## Installation

```
$ npm install @stockmind/vue-brace --save
```


## Examples

```vue
<template>
  <div>
    <brace style="height: 500px"
      :id="'editor1'" 
      :fontsize="'12px'" 
      :theme="'github'" 
      :mode="'json'"
      :codefolding="'markbegin'"
      :softwrap="'free'"
      :selectionstyle="'text'"
      :highlightline="true"
      v-model="sourcecode"
    >
    </brace>
  </div>
</template>

<script>
import Brace from '@stockmind/vue-brace'

export default {
  components: {
    Brace
  }
}
</script>
```

**Note: Give a unique different ID name for every editor you want to place into a page**

## Badges

![](https://img.shields.io/badge/license-MIT-blue.svg)
![](https://img.shields.io/badge/status-dev-yellow.svg)

---