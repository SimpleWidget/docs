# Link

Text link component.

## Basic Usage

```vue
<SLink href="https://example.com">Link</SLink>
<SLink type="primary">Primary Link</SLink>
```

## Types

```vue
<SLink type="default">Default</SLink>
<SLink type="primary">Primary</SLink>
<SLink type="success">Success</SLink>
<SLink type="warning">Warning</SLink>
<SLink type="error">Error</SLink>
```

## Props

| Name | Description | Type | Default |
|------|-------------|------|---------|
| href | Link URL | `string` | - |
| type | Link type | `'default' \| 'primary' \| 'success' \| 'warning' \| 'error'` | `'default'` |
| underline | Show underline | `boolean` | `true` |
| disabled | Disabled state | `boolean` | `false` |