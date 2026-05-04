# Link

Text link component.

## Basic Usage

::: tabs vue3 vue2 react
@tab vue3

```vue
<SLink href="https://example.com">Link</SLink>
<SLink type="primary">Primary Link</SLink>
```

@tab vue2

```vue
<SLink href="https://example.com">Link</SLink>
<SLink type="primary">Primary Link</SLink>
```

@tab react

```tsx
<SLink href="https://example.com">Link</SLink>
<SLink type="primary">Primary Link</SLink>
```
:::

## Types

::: tabs vue3 vue2 react
@tab vue3

```vue
<SLink type="default">Default</SLink>
<SLink type="primary">Primary</SLink>
<SLink type="success">Success</SLink>
<SLink type="warning">Warning</SLink>
<SLink type="error">Error</SLink>
```

@tab vue2

```vue
<SLink type="default">Default</SLink>
<SLink type="primary">Primary</SLink>
<SLink type="success">Success</SLink>
<SLink type="warning">Warning</SLink>
<SLink type="error">Error</SLink>
```

@tab react

```tsx
<SLink type="default">Default</SLink>
<SLink type="primary">Primary</SLink>
<SLink type="success">Success</SLink>
<SLink type="warning">Warning</SLink>
<SLink type="error">Error</SLink>
```
:::

## Props

### Vue3 / Vue2 / React

| Name | Description | Type | Default |
|------|-------------|------|---------|
| href | Link URL | `string` | - |
| type | Link type | `'default' \| 'primary' \| 'success' \| 'warning' \| 'error'` | `'default'` |
| underline | Show underline | `boolean` | `true` |
| disabled | Disabled state | `boolean` | `false` |