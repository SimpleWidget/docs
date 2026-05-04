# Tooltip

Tooltip information component.

## Basic Usage

```vue
<STooltip content="Tooltip content">
  <span>Hover me</span>
</STooltip>
```

## Props

| Name | Description | Type | Default |
|------|-------------|------|---------|
| content | Tooltip content | `string` | - |
| placement | Tooltip position | `'top' \| 'bottom' \| 'left' \| 'right'` | `'top'` |
| trigger | Trigger mode | `'hover' \| 'click' \| 'focus'` | `'hover'` |
| delay | Show delay (ms) | `number` | `0` |

## Slots

| Name | Description |
|------|-------------|
| default | Trigger element |