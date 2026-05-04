# Notification

Global notification component.

## Basic Usage

::: tabs vue3 vue2 react
@tab vue3

```vue
<SNotification
  title="Notification"
  message="This is a notification"
  @close="handleClose"
/>
```

@tab vue2

```vue
<SNotification
  title="Notification"
  message="This is a notification"
  @close="handleClose"
/>
```

@tab react

```tsx
<SNotification
  title="Notification"
  message="This is a notification"
  onClose={handleClose}
/>
```
:::

## Types

::: tabs vue3 vue2 react
@tab vue3

```vue
<SNotification type="success" title="Success" message="Operation successful" />
<SNotification type="warning" title="Warning" message="Warning message" />
<SNotification type="error" title="Error" message="Error occurred" />
<SNotification type="info" title="Info" message="Info message" />
```

@tab vue2

```vue
<SNotification type="success" title="Success" message="Operation successful" />
<SNotification type="warning" title="Warning" message="Warning message" />
<SNotification type="error" title="Error" message="Error occurred" />
<SNotification type="info" title="Info" message="Info message" />
```

@tab react

```tsx
<SNotification type="success" title="Success" message="Operation successful" />
<SNotification type="warning" title="Warning" message="Warning message" />
<SNotification type="error" title="Error" message="Error occurred" />
<SNotification type="info" title="Info" message="Info message" />
```
:::

## Props

### Vue3 / Vue2 / React

| Name | Description | Type | Default |
|------|-------------|------|---------|
| title | Notification title | `string` | - |
| message | Notification content | `string` | - |
| type | Notification type | `'success' \| 'warning' \| 'error' \| 'info'` | `'info'` |
| duration | Display duration (ms) | `number` | `3000` |
| closable | Show close button | `boolean` | `true` |
| position | Position | `'top-right' \| 'top-left' \| 'bottom-right' \| 'bottom-left'` | `'top-right'` |

## Events

### Vue3 / Vue2

| Name | Description |
|------|-------------|
| close | Triggered when closed |

### React

| Name | Description |
|------|-------------|
| onClose | Triggered when closed |