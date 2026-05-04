# Alert

Display important messages to users.

## Basic Usage

::: tabs vue3 vue2 react
@tab vue3

```vue
<SAlert>Default alert message</SAlert>
<SAlert type="success">Success alert message</SAlert>
<SAlert type="warning">Warning alert message</SAlert>
<SAlert type="error">Error alert message</SAlert>
```

@tab vue2

```vue
<SAlert>Default alert message</SAlert>
<SAlert type="success">Success alert message</SAlert>
<SAlert type="warning">Warning alert message</SAlert>
<SAlert type="error">Error alert message</SAlert>
```

@tab react

```tsx
<SAlert>Default alert message</SAlert>
<SAlert type="success">Success alert message</SAlert>
<SAlert type="warning">Warning alert message</SAlert>
<SAlert type="error">Error alert message</SAlert>
```
:::

## With Title

::: tabs vue3 vue2 react
@tab vue3

```vue
<SAlert type="success" title="Success">Operation completed successfully</SAlert>
```

@tab vue2

```vue
<SAlert type="success" title="Success">Operation completed successfully</SAlert>
```

@tab react

```tsx
<SAlert type="success" title="Success">Operation completed successfully</SAlert>
```
:::

## Closable

::: tabs vue3 vue2 react
@tab vue3

```vue
<SAlert closable type="warning" @close="onClose">Closable alert</SAlert>
```

@tab vue2

```vue
<SAlert closable type="warning" @close="onClose">Closable alert</SAlert>
```

@tab react

```tsx
<SAlert closable type="warning" onClose={onClose}>Closable alert</SAlert>
```
:::

## Props

### Vue3 / Vue2 / React

| Name | Description | Type | Default |
|------|-------------|------|---------|
| type | Alert type | `'success' \| 'warning' \| 'error' \| 'info'` | `'info'` |
| title | Alert title | `string` | - |
| closable | Show close button | `boolean` | `false` |
| showIcon | Show icon | `boolean` | `true` |

## Events

### Vue3 / Vue2

| Name | Description |
|------|-------------|
| close | Triggered when closed |

### React

| Name | Description |
|------|-------------|
| onClose | Triggered when closed |