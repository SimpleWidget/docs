# Tag

Tags are used to categorize or mark items.

## Basic Usage

::: details Vue3

```vue
<STag type="primary">Primary</STag>
<STag type="success">Success</STag>
<STag type="danger">Danger</STag>
```

:::

::: details Vue2

```vue
<STag type="primary">Primary</STag>
<STag type="success">Success</STag>
<STag type="danger">Danger</STag>
```

:::

::: details React

```tsx
<STag type="primary">Primary</STag>
<STag type="success">Success</STag>
<STag type="danger">Danger</STag>
```

:::

## Props

| Name | Description | Type | Default |
|------|-------------|------|---------|
| type | Tag type | `'primary' \| 'success' \| 'danger' \| 'warning' \| 'info' \| 'default'` | `'primary'` |
| size | Tag size | `'large' \| 'middle' \| 'small' \| 'mini'` | `'middle'` |
| closable | Show close button | `boolean` | `false` |
| round | Round style | `boolean` | `false` |

## Events

| Name | Description | Vue3 | Vue2 | React |
|------|-------------|------|------|-------|
| close | Close event | `@close` | `@close` | `onClose` |