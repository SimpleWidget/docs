# DatePicker

Date selection component.

## Basic Usage

```vue
<SDatePicker v-model="date" />
```

## Props

| Name | Description | Type | Default |
|------|-------------|------|---------|
| modelValue | Selected date | `Date` | - |
| placeholder | Placeholder text | `string` | `'Select date'` |
| disabled | Disabled state | `boolean` | `false` |
| clearable | Show clear button | `boolean` | `true` |
| format | Date format | `string` | `'YYYY-MM-DD'` |

## Events

| Name | Description |
|------|-------------|
| change | Triggered when date changes |
| clear | Triggered when cleared |