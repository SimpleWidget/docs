# Message

Global message notification.

## Basic Usage

::: tabs vue3 vue2 react
@tab vue3

```vue
<SMessage type="success" message="Success!" />
<SMessage type="error" message="Error occurred" />
<SMessage type="warning" message="Warning!" />
<SMessage type="info" message="Info message" />
```

@tab vue2

```vue
<SMessage type="success" message="Success!" />
<SMessage type="error" message="Error occurred" />
<SMessage type="warning" message="Warning!" />
<SMessage type="info" message="Info message" />
```

@tab react

```tsx
<SMessage type="success" message="Success!" />
<SMessage type="error" message="Error occurred" />
<SMessage type="warning" message="Warning!" />
<SMessage type="info" message="Info message" />
```
:::

## Function Calls

::: tabs vue3 vue2 react
@tab vue3

```ts
SMessage.success('Operation successful')
SMessage.warning('Warning message')
SMessage.error('Error occurred')
SMessage.info('Info message')
```

@tab vue2

```ts
SMessage.success('Operation successful')
SMessage.warning('Warning message')
SMessage.error('Error occurred')
SMessage.info('Info message')
```

@tab react

```tsx
import { SMessage } from 'simplewidget-react'

SMessage.success('Operation successful')
SMessage.warning('Warning message')
SMessage.error('Error occurred')
SMessage.info('Info message')
```
:::

## Props

### Vue3 / Vue2 / React

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