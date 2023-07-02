# Vue tooltip directive

Light tooltip directive for Vue 3.

[FloatingUI](https://floating-ui.com/) is used to position tooltips:
```bash
npm install @floating-ui/dom
```

[Documentation and examples](https://vue-litewind.netlify.app/documentation/tooltip)

### Examples

Directive allows three types of value: `string`, `function` or `object`.
```vue
<button v-tooltip="'Tooltip text'">Button</button>
```
```vue
<button v-tooltip="() => 'Tooltip text'">Button</button>
```
```vue
<button v-tooltip="{ offsetY: 5, text: 'Tooltip text' }">Button</button>
<button v-tooltip="{ offsetY: 5, text: () => 'Tooltip text' }">Button</button>
```
`Object` type offers additional customization options. See [documentation and examples](https://vue-wind.netlify.app/documentation/tooltip) for list of available options.
