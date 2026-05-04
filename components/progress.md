# Progress

Progress indicator component.

## Basic Usage

```vue
<SProgress :percentage="50" />
<SProgress :percentage="80" type="circle" />
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

## Events

| Name | Description |
|------|-------------|
| change | Triggered when percentage changes |