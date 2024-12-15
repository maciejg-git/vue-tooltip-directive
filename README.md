# Vue tooltip directive

Light tooltip directive for Vue 3.

[FloatingUI](https://floating-ui.com/) is used to position tooltips:
```bash
npm install @floating-ui/dom
```

[Documentation and examples](https://vue-litewind.netlify.app/documentation/tooltip)

### Examples

Directive allows three types of value: `string`, `function` or `object`.

`string` is useful for static tooltips:
```vue
<button v-tooltip="'Tooltip text'">Button</button>
```

`function` allows dynamic content:

```vue
<button v-tooltip="() => 'Tooltip text'">Button</button>
```

`object` offers additional customization and FloatingUI options. See [documentation and examples](https://vue-litewind.netlify.app/documentation/tooltip) for list of available options.

```vue
<button v-tooltip="{ offsetY: 5, text: 'Tooltip text' }">Button</button>
<button v-tooltip="{ offsetY: 5, text: () => 'Tooltip text' }">Button</button>
```
