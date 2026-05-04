# Input

Text input component.

## Basic Usage

::: details Vue3

```vue
<SInput v-model="value" placeholder="Please input" />
```

:::

::: details Vue2

```vue
<SInput v-model="value" placeholder="Please input" />
```

:::

::: details React

```tsx
<SInput value={value} onChange={(e) => setValue(e.target.value)} placeholder="Please input" />
```

:::

## Disabled

::: details Vue3

```vue
<SInput disabled placeholder="Disabled" />
```

:::

::: details Vue2

```vue
<SInput disabled placeholder="Disabled" />
```

:::

::: details React

```tsx
<SInput disabled placeholder="Disabled" />
```

:::

## Props

| Name | Description | Type | Default |
|------|-------------|------|---------|
| modelValue / v-model | Input value | `string` | `''` |
| type | Input type | `'text' \| 'password' \| 'number'` | `'text'` |
| placeholder | Placeholder text | `string` | - |
| disabled | Disabled state | `boolean` | `false` |
| clearable | Show clear button | `boolean` | `false` |
| size | Input size | `'large' \| 'middle' \| 'small'` | `'middle'` |

## Events

| Name | Description | Vue3 | Vue2 | React |
|------|-------------|------|------|-------|
| input | Input event | `@input` | `@input` | `onChange` |
| focus | Focus event | `@focus` | `@focus` | `onFocus` |
| blur | Blur event | `@blur` | `@blur` | `onBlur` |