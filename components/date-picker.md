# DatePicker

Date selection component.

## Basic Usage

::: details Vue3

```vue
<SDatePicker v-model="date" />
```

:::

::: details Vue2

```vue
<SDatePicker v-model="date" />
```

:::

::: details React

```tsx
<SDatePicker value={date} onChange={setDate} />
```

:::

## Props

| Name | Description | Type | Default |
|------|-------------|------|---------|
| modelValue / v-model / value | Selected date | `Date` | - |
| placeholder | Placeholder text | `string` | `'Select date'` |
| disabled | Disabled state | `boolean` | `false` |
| clearable | Show clear button | `boolean` | `true` |
| format | Date format | `string` | `'YYYY-MM-DD'` |

## Events

| Name | Description | Vue3 | Vue2 | React |
|------|-------------|------|------|-------|
| change | Date change | `@change` | `@change` | `onChange` |