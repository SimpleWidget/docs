# Alert

Display important messages to users.

## Basic Usage

::: details Vue3

```vue
<SAlert type="success">Success message</SAlert>
<SAlert type="warning">Warning message</SAlert>
<SAlert type="error">Error message</SAlert>
```

:::

::: details Vue2

```vue
<SAlert type="success">Success message</SAlert>
<SAlert type="warning">Warning message</SAlert>
<SAlert type="error">Error message</SAlert>
```

:::

::: details React

```tsx
<SAlert type="success">Success message</SAlert>
<SAlert type="warning">Warning message</SAlert>
<SAlert type="error">Error message</SAlert>
```

:::

## Props

| Name | Description | Type | Default |
|------|-------------|------|---------|
| type | Alert type | `'success' \| 'warning' \| 'error' \| 'info'` | `'info'` |
| title | Alert title | `string` | - |
| closable | Show close button | `boolean` | `false` |

## Events

| Name | Description | Vue3 | Vue2 | React |
|------|-------------|------|------|-------|
| close | Close event | `@close` | `@close` | `onClose` |