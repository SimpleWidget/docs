# Checkbox

Select one or more options.

## Basic Usage

```vue
<SCheckbox v-model="checked">Option</SCheckbox>
```

## Props

| Name | Description | Type | Default |
|------|-------------|------|---------|
| modelValue | Checked state | `boolean` | `false` |
| label | Checkbox label | `string` | - |
| disabled | Disabled state | `boolean` | `false` |
| indeterminate | Indeterminate state | `boolean` | `false` |

## Events

| Name | Description |
|------|-------------|
| change | Triggered when checked state changes |