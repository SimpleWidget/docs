# Watermark

Watermark overlay component.

## Basic Usage

::: tabs vue3 vue2 react
@tab vue3

```vue
<SWatermark content="Watermark text" />
```

@tab vue2

```vue
<SWatermark content="Watermark text" />
```

@tab react

```tsx
<SWatermark content="Watermark text" />
```
:::

## Custom Styling

::: tabs vue3 vue2 react
@tab vue3

```vue
<SWatermark content="Watermark" :opacity="0.3" :rotate="-30" color="#1890ff" />
```

@tab vue2

```vue
<SWatermark content="Watermark" :opacity="0.3" :rotate="-30" color="#1890ff" />
```

@tab react

```tsx
<SWatermark content="Watermark" opacity={0.3} rotate={-30} color="#1890ff" />
```
:::

## Props

### Vue3 / Vue2 / React

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