# Image

Image display component.

## Basic Usage

::: tabs vue3 vue2 react
@tab vue3

```vue
<SImage src="https://example.com/image.jpg" />
```

@tab vue2

```vue
<SImage src="https://example.com/image.jpg" />
```

@tab react

```tsx
<SImage src="https://example.com/image.jpg" />
```
:::

## Fit Modes

::: tabs vue3 vue2 react
@tab vue3

```vue
<SImage src="https://example.com/image.jpg" fit="contain" />
<SImage src="https://example.com/image.jpg" fit="cover" />
<SImage src="https://example.com/image.jpg" fit="fill" />
```

@tab vue2

```vue
<SImage src="https://example.com/image.jpg" fit="contain" />
<SImage src="https://example.com/image.jpg" fit="cover" />
<SImage src="https://example.com/image.jpg" fit="fill" />
```

@tab react

```tsx
<SImage src="https://example.com/image.jpg" fit="contain" />
<SImage src="https://example.com/image.jpg" fit="cover" />
<SImage src="https://example.com/image.jpg" fit="fill" />
```
:::

## Props

### Vue3 / Vue2 / React

| Name | Description | Type | Default |
|------|-------------|------|---------|
| src | Image URL | `string` | - |
| alt | Alt text | `string` | - |
| fit | Object-fit mode | `'fill' \| 'contain' \| 'cover' \| 'none'` | `'cover'` |
| width | Image width | `string` | - |
| height | Image height | `string` | - |
| lazy | Lazy load | `boolean` | `false` |

## Events

### Vue3 / Vue2

| Name | Description |
|------|-------------|
| load | Triggered when image loads |
| error | Triggered when image fails |

### React

| Name | Description |
|------|-------------|
| onLoad | Triggered when image loads |
| onError | Triggered when image fails |