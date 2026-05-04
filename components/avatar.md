# Avatar

Display user avatar or fallback.

## Basic Usage

```vue
<SAvatar src="https://example.com/avatar.jpg" />
<SAvatar name="John Doe" />
```

## Sizes

```vue
<SAvatar name="Large" size="large" />
<SAvatar name="Middle" size="middle" />
<SAvatar name="Small" size="small" />
```

## Props

| Name | Description | Type | Default |
|------|-------------|------|---------|
| src | Image URL | `string` | - |
| name | Display name | `string` | - |
| size | Avatar size | `'large' \| 'middle' \| 'small'` | `'middle'` |
| shape | Shape | `'circle' \| 'square'` | `'circle'` |

## Events

| Name | Description |
|------|-------------|
| error | Triggered when image fails to load |