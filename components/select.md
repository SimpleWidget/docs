# Select

Dropdown selection component.

## Basic Usage

```vue
<SSelect v-model="value" placeholder="Please select">
  <SOption label="Option 1" value="1" />
  <SOption label="Option 2" value="2" />
</SSelect>
```

## Props

| Name | Description | Type | Default |
|------|-------------|------|---------|
| modelValue | Selected value | `string \| number` | - |
| placeholder | Placeholder text | `string` | `'Please select'` |
| disabled | Disabled state | `boolean` | `false` |
| clearable | Show clear button | `boolean` | `false` |
| filterable | Enable filtering | `boolean` | `false` |
| size | Select size | `'large' \| 'middle' \| 'small'` | `'middle'` |

## Option Props

| Name | Description | Type | Default |
|------|-------------|------|---------|
| label | Option label | `string` | - |
| value | Option value | `string \| number` | - |
| disabled | Disabled state | `boolean` | `false` |

## Events

| Name | Description |
|------|-------------|
| change | Triggered when selection changes |
| focus | Triggered on focus |
| blur | Triggered on blur |
| clear | Triggered when cleared |
| visibleChange | Triggered when dropdown visibility changes |