# Image

Image display component.

## Basic Usage

```vue
<SImage src="https://example.com/image.jpg" />
```

## Props

| Name | Description | Type | Default |
|------|-------------|------|---------|
| src | Image URL | `string` | - |
| alt | Alt text | `string` | - |
| fit | Object-fit mode | `'fill' \| 'contain' \| 'cover' \| 'none'` | `'cover'` |
| width | Image width | `string` | - |
| height | Image height | `string` | - |
| lazy | Lazy load | `boolean` | `false` |

## Events

| Name | Description |
|------|-------------|
| load | Triggered when image loads |
| error | Triggered when image fails |