# Avatar

Display user avatar or fallback.

## Basic Usage

::: details Vue3

```vue
<SAvatar src="https://example.com/avatar.jpg" />
<SAvatar name="John Doe" />
```

:::

::: details Vue2

```vue
<SAvatar src="https://example.com/avatar.jpg" />
<SAvatar name="John Doe" />
```

:::

::: details React

```tsx
<SAvatar src="https://example.com/avatar.jpg" />
<SAvatar name="John Doe" />
```

:::

## Props

| Name | Description | Type | Default |
|------|-------------|------|---------|
| src | Image URL | `string` | - |
| name | Display name | `string` | - |
| size | Avatar size | `'large' \| 'middle' \| 'small'` | `'middle'` |
| shape | Shape | `'circle' \| 'square'` | `'circle'` |

## Events

| Name | Description | Vue3 | Vue2 | React |
|------|-------------|------|------|-------|
| error | Image error | `@error` | `@error` | `onError` |