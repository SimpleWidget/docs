# Calendar

Display calendar for date selection.

## Basic Usage

```vue
<SCalendar v-model="date" />
```

## Props

| Name | Description | Type | Default |
|------|-------------|------|---------|
| modelValue / v-model | Selected date | `Date` | - |
| minDate | Minimum date | `Date` | - |
| maxDate | Maximum date | `Date` | - |
| showToday | Show today button | `boolean` | `true` |

## Events

| Name | Description |
|------|-------------|
| change | Triggered when date changes |

## React Props Difference

| Name | Description | Type | Default |
|------|-------------|------|---------|
| value | Selected date | `Date` | - |
| onChange | Change handler | `(date: Date) => void` | - |