# Calendar

Display calendar for date selection.

## Basic Usage

::: details Vue3

```vue
<SCalendar v-model="date" />
```

:::

::: details Vue2

```vue
<SCalendar v-model="date" />
```

:::

::: details React

```tsx
<SCalendar value={date} onChange={setDate} />
```

:::

## Props

| Name | Description | Type | Default |
|------|-------------|------|---------|
| modelValue / v-model / value | Selected date | `Date` | - |
| minDate | Minimum date | `Date` | - |
| maxDate | Maximum date | `Date` | - |

## Events

| Name | Description | Vue3 | Vue2 | React |
|------|-------------|------|------|-------|
| change | Date change | `@change` | `@change` | `onChange` |