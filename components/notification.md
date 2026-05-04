# Notification

Global notification component.

## Basic Usage

::: details Vue3

```vue
<SNotification
  title="Notification"
  message="This is a notification"
  @close="handleClose"
/>
```

:::

::: details Vue2

```vue
<SNotification
  title="Notification"
  message="This is a notification"
  @close="handleClose"
/>
```

:::

::: details React

```tsx
<SNotification
  title="Notification"
  message="This is a notification"
  onClose={handleClose}
/>
```

:::

## Props

| Name | Description | Type | Default |
|------|-------------|------|---------|
| title | Notification title | `string` | - |
| message | Notification content | `string` | - |
| type | Notification type | `'success' \| 'warning' \| 'error' \| 'info'` | `'info'` |
| duration | Display duration (ms) | `number` | `3000` |
| position | Position | `'top-right' \| 'top-left' \| 'bottom-right' \| 'bottom-left'` | `'top-right'` |

## Events

| Name | Description | Vue3 | Vue2 | React |
|------|-------------|------|------|-------|
| close | Close event | `@close` | `@close` | `onClose` |