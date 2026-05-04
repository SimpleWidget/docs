# Image

Image display component.

## Basic Usage

::: details Vue3

```vue
<SImage src="https://example.com/image.jpg" />
```

:::

::: details Vue2

```vue
<SImage src="https://example.com/image.jpg" />
```

:::

::: details React

```tsx
<SImage src="https://example.com/image.jpg" />
```

:::

## Props

| Name | Description | Type | Default |
|------|-------------|------|---------|
| src | Image URL | `string` | - |
| alt | Alt text | `string` | - |
| fit | Object-fit mode | `'fill' \| 'contain' \| 'cover' \| 'none'` | `'cover'` |
| lazy | Lazy load | `boolean` | `false` |

## Events

| Name | Description | Vue3 | Vue2 | React |
|------|-------------|------|------|-------|
| load | Image loaded | `@load` | `@load` | `onLoad` |
| error | Load error | `@error` | `@error` | `onError` |