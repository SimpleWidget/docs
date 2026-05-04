# Checkbox Group

Group of checkboxes.

## Basic Usage

```vue
<SCheckboxGroup v-model="values" :options="['A', 'B', 'C']" />
```

## With Labels

```vue
<SCheckboxGroup v-model="values" :options="options" />
```

## Props

| Name | Description | Type | Default |
|------|-------------|------|---------|
| modelValue / v-model | Selected values | `string[]` | `[]` |
| options | Options array | `string[] \| object[]` | `[]` |
| disabled | Disabled state | `boolean` | `false` |

## Events

| Name | Description |
|------|-------------|
| change | Triggered when selection changes |

## React Props Difference

| Name | Description | Type | Default |
|------|-------------|------|---------|
| value | Selected values | `string[]` | `[]` |
| onChange | Change handler | `(values: string[]) => void` | - |