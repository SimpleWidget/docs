# Select

Select component for choosing from options.

## Basic Usage

::: tabs vue3 vue2 react
@tab vue3

```vue
<SSelect v-model="value" placeholder="Please select">
  <SOption label="Option 1" value="1" />
  <SOption label="Option 2" value="2" />
  <SOption label="Option 3" value="3" />
</SSelect>
```

@tab vue2

```vue
<SSelect v-model="value" placeholder="Please select">
  <SOption label="Option 1" value="1" />
  <SOption label="Option 2" value="2" />
  <SOption label="Option 3" value="3" />
</SSelect>
```

@tab react

```tsx
<SSelect value={value} onChange={setValue} placeholder="Please select">
  <SOption label="Option 1" value="1" />
  <SOption label="Option 2" value="2" />
  <SOption label="Option 3" value="3" />
</SSelect>
```
:::

## Disabled

::: tabs vue3 vue2 react
@tab vue3

```vue
<SSelect disabled v-model="value" placeholder="Disabled" />
```

@tab vue2

```vue
<SSelect disabled v-model="value" placeholder="Disabled" />
```

@tab react

```tsx
<SSelect disabled value={value} onChange={setValue} placeholder="Disabled" />
```
:::

## Clearable

::: tabs vue3 vue2 react
@tab vue3

```vue
<SSelect clearable v-model="value" placeholder="Clearable">
  <SOption label="Option 1" value="1" />
  <SOption label="Option 2" value="2" />
</SSelect>
```

@tab vue2

```vue
<SSelect clearable v-model="value" placeholder="Clearable">
  <SOption label="Option 1" value="1" />
  <SOption label="Option 2" value="2" />
</SSelect>
```

@tab react

```tsx
<SSelect clearable value={value} onChange={setValue} placeholder="Clearable">
  <SOption label="Option 1" value="1" />
  <SOption label="Option 2" value="2" />
</SSelect>
```
:::

## Props

### Vue3 / Vue2

| Name | Description | Type | Default |
|------|-------------|------|---------|
| modelValue / v-model | Selected value | `string \| number` | - |
| placeholder | Placeholder text | `string` | - |
| disabled | Disabled state | `boolean` | `false` |
| clearable | Show clear button | `boolean` | `false` |
| filterable | Enable search | `boolean` | `false` |
| size | Select size | `'large' \| 'middle' \| 'small'` | `'middle'` |

### React

| Name | Description | Type | Default |
|------|-------------|------|---------|
| value | Selected value | `string \| number` | - |
| onChange | Change handler | `(value: string \| number) => void` | - |
| placeholder | Placeholder text | `string` | - |
| disabled | Disabled state | `boolean` | `false` |
| clearable | Show clear button | `boolean` | `false` |
| filterable | Enable search | `boolean` | `false` |
| size | Select size | `'large' \| 'middle' \| 'small'` | `'middle'` |