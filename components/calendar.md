# Calendar

Display calendar for date selection.

## Basic Usage

```vue
<SCalendar v-model="date" />
```

## Props

| Name | Description | Type | Default |
|------|-------------|------|---------|
| modelValue | Selected date | `Date` | - |
| minDate | Minimum date | `Date` | - |
| maxDate | Maximum date | `Date` | - |
| showToday | Show today button | `boolean` | `true` |

## Events

| Name | Description |
|------|-------------|
| change | Triggered when date changes |