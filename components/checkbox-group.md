# Checkbox Group

Group of checkboxes.

## Basic Usage

```vue
<SCheckboxGroup v-model="values" :options="['A', 'B', 'C']" />
```

## Props

| Name | Description | Type | Default |
|------|-------------|------|---------|
| modelValue | Selected values | `string[]` | `[]` |
| options | Options array | `string[]` | `[]` |
| disabled | Disabled state | `boolean` | `false` |

## Events

| Name | Description |
|------|-------------|
| change | Triggered when selection changes |