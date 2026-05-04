# Alert

Display important messages to users.

## Basic Usage

```vue
<SAlert type="success">Success message</SAlert>
<SAlert type="warning">Warning message</SAlert>
<SAlert type="error">Error message</SAlert>
<SAlert type="info">Info message</SAlert>
```

## With Title

```vue
<SAlert type="success" title="Success">Operation completed</SAlert>
```

## Closable

```vue
<SAlert closable type="warning" @close="onClose">Closable alert</SAlert>
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

## React Props Difference

| Name | Description | Type | Default |
|------|-------------|------|---------|
| onClose | Close handler | `() => void` | - |