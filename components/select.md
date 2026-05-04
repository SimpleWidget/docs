# Select

Select component for choosing from options.

## Basic Usage

::: details Vue3

```vue
<SSelect v-model="value" placeholder="Please select">
  <SOption label="Option 1" value="1" />
  <SOption label="Option 2" value="2" />
</SSelect>
```

:::

::: details Vue2

```vue
<SSelect v-model="value" placeholder="Please select">
  <SOption label="Option 1" value="1" />
  <SOption label="Option 2" value="2" />
</SSelect>
```

:::

::: details React

```tsx
<SSelect value={value} onChange={setValue} placeholder="Please select">
  <SOption label="Option 1" value="1" />
  <SOption label="Option 2" value="2" />
</SSelect>
```

:::

## Disabled

::: details Vue3

```vue
<SSelect disabled v-model="value" placeholder="Disabled" />
```

:::

::: details Vue2

```vue
<SSelect disabled v-model="value" placeholder="Disabled" />
```

:::

::: details React

```tsx
<SSelect disabled value={value} onChange={setValue} placeholder="Disabled" />
```

:::

## Props

| Name | Description | Type | Default |
|------|-------------|------|---------|
| modelValue / v-model | Selected value | `string \| number` | - |
| placeholder | Placeholder text | `string` | - |
| disabled | Disabled state | `boolean` | `false` |
| clearable | Show clear button | `boolean` | `false` |
| filterable | Enable search | `boolean` | `false` |
| size | Select size | `'large' \| 'middle' \| 'small'` | `'middle'` |

## Events

| Name | Description | Vue3 | Vue2 | React |
|------|-------------|------|------|-------|
| change | Selection change | `@change` | `@change` | `onChange` |