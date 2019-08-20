
> **Everything you wish the HTML `<select>` element could do, wrapped up into a lightweight, zero 
dependency, extensible Vue component.** 

- Tagging
- Filtering / Searching
- Vuex Support
- AJAX Support
- SSR Support
- ~20kb Total / ~5kb CSS / ~15kb JS
- Select Single/Multiple Options
- Customizable with slots and SCSS variables
- Tested with Bootstrap 3/4, Bulma, Foundation
- +95% Test Coverage
- Zero dependencies

## Documentation

Complete documentation and examples available at https://vue-select.org.

- **[API Documentation](https://vue-select.org)**
- **[Sandbox Demo](https://vue-select.org/sandbox.html)**
- **[CodePen Template](http://codepen.io/sagalbot/pen/NpwrQO)**
- **[GitHub Projects](https://github.com/sujith2014/vue-select/projects)**

## Install

```bash
$ npm install @sujithz/vue-select
```

Register the component

```js
import Vue from 'vue'
import vSelect from 'vue-select'

Vue.component('v-select', vSelect)
```

You may now use the component in your markup

```html
<v-select v-model="selected" :options="['Vue.js','React']"></v-select>
```

You can also include vue-select directly in the browser. Check out the 
[documentation for loading from CDN.](https://vue-select.org/guide/install.html#in-the-browser).

## License

[MIT](https://github.com/sujith2014/vue-select/blob/master/LICENSE.md)
# vue-select
