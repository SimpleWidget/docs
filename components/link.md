# Link

Text link component.

## Basic Usage

::: details Vue3

```vue
<SLink href="https://example.com">Link</SLink>
<SLink type="primary">Primary Link</SLink>
```

:::

::: details Vue2

```vue
<SLink href="https://example.com">Link</SLink>
<SLink type="primary">Primary Link</SLink>
```

:::

::: details React

```tsx
<SLink href="https://example.com">Link</SLink>
<SLink type="primary">Primary Link</SLink>
```

:::

## Props

| Name | Description | Type | Default |
|------|-------------|------|---------|
| href | Link URL | `string` | - |
| type | Link type | `'default' \| 'primary' \| 'success' \| 'warning' \| 'error'` | `'default'` |
| disabled | Disabled state | `boolean` | `false` |