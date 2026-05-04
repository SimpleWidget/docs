# Message

Global message notification.

## Basic Usage

```vue
<SMessage type="success" message="Success!" />
<SMessage type="error" message="Error occurred" />
```

## Props

| Name | Description | Type | Default |
|------|-------------|------|---------|
| type | Message type | `'success' \| 'warning' \| 'error' \| 'info'` | `'info'` |
| message | Message content | `string` | - |
| duration | Display duration (ms) | `number` | `3000` |
| closable | Show close button | `boolean` | `false` |

## Functions

| Name | Description |
|------|-------------|
| SMessage.success(msg) | Show success message |
| SMessage.warning(msg) | Show warning message |
| SMessage.error(msg) | Show error message |
| SMessage.info(msg) | Show info message |