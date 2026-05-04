# Watermark

Watermark overlay component.

## Basic Usage

```vue
<SWatermark content="Watermark text" />
```

## Props

| Name | Description | Type | Default |
|------|-------------|------|---------|
| content | Watermark text | `string` | - |
| width | Watermark width | `number` | `200` |
| height | Watermark height | `number` | `100` |
| opacity | Watermark opacity | `number` | `0.2` |
| color | Watermark color | `string` | `'#000'` |
| rotate | Rotation angle | `number` | `-45` |
| fontSize | Font size | `number` | `16` |
| fontFamily | Font family | `string` | `'sans-serif'` |
| zIndex | Z-index | `number` | `1000` |

## Slots

| Name | Description |
|------|-------------|
| default | Content to overlay |