# Alert

Display important messages to users.

## Basic Usage

```vue
<SAlert>Default alert message</SAlert>
<SAlert type="success">Success alert message</SAlert>
<SAlert type="warning">Warning alert message</SAlert>
<SAlert type="error">Error alert message</SAlert>
```

## Props

| Name | Description | Type | Default |
|------|-------------|------|---------|
| type | Alert type | `'success' \| 'warning' \| 'error' \| 'info'` | `'info'` |
| title | Alert title | `string` | - |
| closable | Show close button | `boolean` | `false` |
| showIcon | Show icon | `boolean` | `true` |

## Events

| Name | Description |
|------|-------------|
| close | Triggered when closed |