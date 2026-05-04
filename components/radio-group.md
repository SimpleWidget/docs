# Radio Group

Group of radio buttons.

## Basic Usage

```vue
<SRadioGroup v-model="value" :options="['A', 'B', 'C']" />
```

## With Options

```vue
<SRadioGroup v-model="value" :options="options" />
```

## Props

| Name | Description | Type | Default |
|------|-------------|------|---------|
| modelValue / v-model | Selected value | `string \| number` | - |
| options | Options array | `string[] \| number[]` | `[]` |
| disabled | Disabled state | `boolean` | `false` |
| size | Group size | `'large' \| 'middle' \| 'small'` | `'middle'` |

## Events

| Name | Description |
|------|-------------|
| change | Triggered when selection changes |

## React Props Difference

| Name | Description | Type | Default |
|------|-------------|------|---------|
| value | Selected value | `string \| number` | - |
| onChange | Change handler | `(value: string \| number) => void` | - |