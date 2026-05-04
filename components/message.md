# Message

Global message notification.

## Basic Usage

::: details Vue3

```vue
<SMessage type="success" message="Success!" />
<SMessage type="error" message="Error!" />
```

:::

::: details Vue2

```vue
<SMessage type="success" message="Success!" />
<SMessage type="error" message="Error!" />
```

:::

::: details React

```tsx
<SMessage type="success" message="Success!" />
<SMessage type="error" message="Error!" />
```

:::

## Function Call

::: details Vue3

```ts
SMessage.success('Operation successful')
SMessage.error('Error occurred')
```

:::

::: details Vue2

```ts
SMessage.success('Operation successful')
SMessage.error('Error occurred')
```

:::

::: details React

```tsx
import { SMessage } from 'simplewidget-react'

SMessage.success('Operation successful')
SMessage.error('Error occurred')
```

:::

## Props

| Name | Description | Type | Default |
|------|-------------|------|---------|
| type | Message type | `'success' \| 'warning' \| 'error' \| 'info'` | `'info'` |
| message | Message content | `string` | - |
| duration | Display duration (ms) | `number` | `3000` |