# Watermark

Watermark overlay component.

## Basic Usage

```vue
<SWatermark content="Watermark text" />
```

## Custom Styling

```vue
<SWatermark content="Watermark" :opacity="0.3" :rotate="-30" color="#1890ff" />
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