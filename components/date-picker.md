# DatePicker

Date selection component.

## Basic Usage

::: tabs vue3 vue2 react
@tab vue3

```vue
<SDatePicker v-model="date" />
```

@tab vue2

```vue
<SDatePicker v-model="date" />
```

@tab react

```tsx
<SDatePicker value={date} onChange={setDate} />
```
:::

## Placeholder

::: tabs vue3 vue2 react
@tab vue3

```vue
<SDatePicker v-model="date" placeholder="Select date" />
```

@tab vue2

```vue
<SDatePicker v-model="date" placeholder="Select date" />
```

@tab react

```tsx
<SDatePicker value={date} onChange={setDate} placeholder="Select date" />
```
:::

## Props

### Vue3 / Vue2 / React

| Name | Description | Type | Default |
|------|-------------|------|---------|
| modelValue / v-model / value | Selected date | `Date` | - |
| placeholder | Placeholder text | `string` | `'Select date'` |
| disabled | Disabled state | `boolean` | `false` |
| clearable | Show clear button | `boolean` | `true` |
| format | Date format | `string` | `'YYYY-MM-DD'` |

## Events

### Vue3 / Vue2

| Name | Description |
|------|-------------|
| change | Triggered when date changes |
| clear | Triggered when cleared |

### React

| Name | Description |
|------|-------------|
| onChange | Triggered when date changes |
| onClear | Triggered when cleared |