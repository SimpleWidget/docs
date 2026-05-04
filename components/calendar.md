# Calendar

Display calendar for date selection.

## Basic Usage

::: tabs vue3 vue2 react
@tab vue3

```vue
<SCalendar v-model="date" />
```

@tab vue2

```vue
<SCalendar v-model="date" />
```

@tab react

```tsx
<SCalendar value={date} onChange={setDate} />
```
:::

## Props

### Vue3 / Vue2 / React

| Name | Description | Type | Default |
|------|-------------|------|---------|
| modelValue / v-model / value | Selected date | `Date` | - |
| minDate | Minimum date | `Date` | - |
| maxDate | Maximum date | `Date` | - |
| showToday | Show today button | `boolean` | `true` |

## Events

### Vue3 / Vue2

| Name | Description |
|------|-------------|
| change | Triggered when date changes |

### React

| Name | Description |
|------|-------------|
| onChange | Triggered when date changes |