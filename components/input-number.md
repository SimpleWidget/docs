# InputNumber

Number input component.

## Basic Usage

```vue
<SInputNumber v-model="num" :min="0" :max="100" />
```

## Props

| Name | Description | Type | Default |
|------|-------------|------|---------|
| modelValue | Current value | `number` | `0` |
| min | Minimum value | `number` | `-Infinity` |
| max | Maximum value | `number` | `Infinity` |
| step | Step value | `number` | `1` |
| precision | Decimal precision | `number` | - |
| disabled | Disabled state | `boolean` | `false` |
| size | Input size | `'large' \| 'middle' \| 'small'` | `'middle'` |

## Events

| Name | Description |
|------|-------------|
| change | Triggered when value changes |