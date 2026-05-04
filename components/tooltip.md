# Tooltip

Tooltip information component.

## Basic Usage

```vue
<STooltip content="Tooltip content">
  <span>Hover me</span>
</STooltip>
```

## Positions

```vue
<STooltip content="Top" placement="top">Top</STooltip>
<STooltip content="Bottom" placement="bottom">Bottom</STooltip>
<STooltip content="Left" placement="left">Left</STooltip>
<STooltip content="Right" placement="right">Right</STooltip>
```

## Props

| Name | Description | Type | Default |
|------|-------------|------|---------|
| content | Tooltip content | `string` | - |
| placement | Tooltip position | `'top' \| 'bottom' \| 'left' \| 'right'` | `'top'` |
| trigger | Trigger mode | `'hover' \| 'click' \| 'focus'` | `'hover'` |
| delay | Show delay (ms) | `number` | `0` |