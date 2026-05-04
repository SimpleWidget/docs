# Radio Group

Group of radio buttons.

## Basic Usage

```vue
<SRadioGroup v-model="value" :options="['A', 'B', 'C']" />
```

## Props

| Name | Description | Type | Default |
|------|-------------|------|---------|
| modelValue | Selected value | `string \| number` | - |
| options | Options array | `string[] \| number[]` | `[]` |
| disabled | Disabled state | `boolean` | `false` |
| size | Group size | `'large' \| 'middle' \| 'small'` | `'middle'` |

## Events

| Name | Description |
|------|-------------|
| change | Triggered when selection changes |