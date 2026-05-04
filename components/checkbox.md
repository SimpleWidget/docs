# Checkbox

Select one or more options.

## Basic Usage

```vue
<SCheckbox v-model="checked">Option</SCheckbox>
```

## Disabled

```vue
<SCheckbox disabled v-model="checked">Disabled</SCheckbox>
```

## Group

```vue
<SCheckboxGroup v-model="checkedList">
  <SCheckbox label="Option A" value="a" />
  <SCheckbox label="Option B" value="b" />
  <SCheckbox label="Option C" value="c" />
</SCheckboxGroup>
```

## Props

| Name | Description | Type | Default |
|------|-------------|------|---------|
| modelValue / v-model | Checked state | `boolean` | `false` |
| label | Checkbox label | `string` | - |
| disabled | Disabled state | `boolean` | `false` |
| indeterminate | Indeterminate state | `boolean` | `false` |
| value | Checkbox value (in group) | `string \| number` | - |

## Events

| Name | Description |
|------|-------------|
| change | Triggered when checked state changes |

## React Props Difference

| Name | Description | Type | Default |
|------|-------------|------|---------|
| checked | Checked state | `boolean` | `false` |
| onChange | Change handler | `(checked: boolean) => void` | - |