# DatePicker

Date selection component.

## Basic Usage

```vue
<SDatePicker v-model="date" />
```

## Placeholder

```vue
<SDatePicker v-model="date" placeholder="Select date" />
```

## Props

| Name | Description | Type | Default |
|------|-------------|------|---------|
| modelValue / v-model | Selected date | `Date` | - |
| placeholder | Placeholder text | `string` | `'Select date'` |
| disabled | Disabled state | `boolean` | `false` |
| clearable | Show clear button | `boolean` | `true` |
| format | Date format | `string` | `'YYYY-MM-DD'` |

## Events

| Name | Description |
|------|-------------|
| change | Triggered when date changes |
| clear | Triggered when cleared |

## React Props Difference

| Name | Description | Type | Default |
|------|-------------|------|---------|
| value | Selected date | `Date` | - |
| onChange | Change handler | `(date: Date) => void` | - |