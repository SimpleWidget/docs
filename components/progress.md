# Progress

Progress indicator component.

## Basic Usage

```vue
<SProgress :percentage="50" />
<SProgress :percentage="80" type="circle" />
```

## With Color

```vue
<SProgress :percentage="70" color="#67c23a" />
<SProgress :percentage="50" type="circle" color="#e6a23c" />
```

## Props

| Name | Description | Type | Default |
|------|-------------|------|---------|
| percentage | Progress percentage | `number` | `0` |
| type | Progress type | `'line' \| 'circle' \| 'dashboard'` | `'line'` |
| strokeWidth | Stroke width | `number` | `6` |
| color | Progress color | `string` | - |
| trackColor | Track color | `string` | - |
| showText | Show percentage text | `boolean` | `true` |