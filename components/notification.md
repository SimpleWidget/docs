# Notification

Global notification component.

## Basic Usage

```vue
<SNotification
  title="Notification"
  message="This is a notification"
  @close="handleClose"
/>
```

## Props

| Name | Description | Type | Default |
|------|-------------|------|---------|
| title | Notification title | `string` | - |
| message | Notification content | `string` | - |
| type | Notification type | `'success' \| 'warning' \| 'error' \| 'info'` | `'info'` |
| duration | Display duration (ms) | `number` | `3000` |
| closable | Show close button | `boolean` | `true` |
| position | Position | `'top-right' \| 'top-left' \| 'bottom-right' \| 'bottom-left'` | `'top-right'` |

## Events

| Name | Description |
|------|-------------|
| close | Triggered when closed |