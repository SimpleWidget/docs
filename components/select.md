# Select

Select component for choosing from options.

## Basic Usage

```vue
<SSelect v-model="value" placeholder="Please select">
  <SOption label="Option 1" value="1" />
  <SOption label="Option 2" value="2" />
  <SOption label="Option 3" value="3" />
</SSelect>
```

## Disabled

```vue
<SSelect disabled v-model="value" placeholder="Disabled" />
```

## Clearable

```vue
<SSelect clearable v-model="value" placeholder="Clearable">
  <SOption label="Option 1" value="1" />
  <SOption label="Option 2" value="2" />
</SSelect>
```

## Props

| Name | Description | Type | Default |
|------|-------------|------|---------|
| modelValue / v-model | Selected value | `string \| number` | - |
| placeholder | Placeholder text | `string` | - |
| disabled | Disabled state | `boolean` | `false` |
| clearable | Show clear button | `boolean` | `false` |
| filterable | Enable search | `boolean` | `false` |
| size | Select size | `'large' \| 'middle' \| 'small'` | `'middle'` |

## React Props Difference

| Name | Description | Type | Default |
|------|-------------|------|---------|
| value | Selected value | `string \| number` | - |
| onChange | Change handler | `(value: string \| number) => void` | - |