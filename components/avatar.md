# Avatar

Display user avatar or fallback.

## Basic Usage

::: tabs vue3 vue2 react
@tab vue3

```vue
<SAvatar src="https://example.com/avatar.jpg" />
<SAvatar name="John Doe" />
```

@tab vue2

```vue
<SAvatar src="https://example.com/avatar.jpg" />
<SAvatar name="John Doe" />
```

@tab react

```tsx
<SAvatar src="https://example.com/avatar.jpg" />
<SAvatar name="John Doe" />
```
:::

## Sizes

::: tabs vue3 vue2 react
@tab vue3

```vue
<SAvatar name="Large" size="large" />
<SAvatar name="Middle" size="middle" />
<SAvatar name="Small" size="small" />
```

@tab vue2

```vue
<SAvatar name="Large" size="large" />
<SAvatar name="Middle" size="middle" />
<SAvatar name="Small" size="small" />
```

@tab react

```tsx
<SAvatar name="Large" size="large" />
<SAvatar name="Middle" size="middle" />
<SAvatar name="Small" size="small" />
```
:::

## Props

### Vue3 / Vue2 / React

| Name | Description | Type | Default |
|------|-------------|------|---------|
| src | Image URL | `string` | - |
| name | Display name | `string` | - |
| size | Avatar size | `'large' \| 'middle' \| 'small'` | `'middle'` |
| shape | Shape | `'circle' \| 'square'` | `'circle'` |

## Events

### Vue3 / Vue2

| Name | Description |
|------|-------------|
| error | Triggered when image fails to load |

### React

| Name | Description |
|------|-------------|
| onError | Triggered when image fails to load |