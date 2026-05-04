# Message

Global message notification.

## Basic Usage

```vue
<SMessage type="success" message="Success!" />
<SMessage type="error" message="Error occurred" />
<SMessage type="warning" message="Warning!" />
<SMessage type="info" message="Info message" />
```

## Function Calls

```ts
SMessage.success('Operation successful')
SMessage.warning('Warning message')
SMessage.error('Error occurred')
SMessage.info('Info message')
```

## Props

| Name | Description | Type | Default |
|------|-------------|------|---------|
| type | Message type | `'success' \| 'warning' \| 'error' \| 'info'` | `'info'` |
| message | Message content | `string` | - |
| duration | Display duration (ms) | `number` | `3000` |
| closable | Show close button | `boolean` | `false` |