# Link

Text link component.

## Basic Usage

```vue
<SLink href="https://example.com">Link</SLink>
<SLink type="primary">Primary Link</SLink>
```

## Props

| Name | Description | Type | Default |
|------|-------------|------|---------|
| href | Link URL | `string` | - |
| type | Link type | `'default' \| 'primary' \| 'success' \| 'warning' \| 'error'` | `'default'` |
| underline | Show underline | `boolean` | `true` |
| disabled | Disabled state | `boolean` | `false` |