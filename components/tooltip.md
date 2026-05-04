# Tooltip

Tooltip information component.

## Basic Usage

::: details Vue3

```vue
<STooltip content="Tooltip content">
  <span>Hover me</span>
</STooltip>
```

:::

::: details Vue2

```vue
<STooltip content="Tooltip content">
  <span>Hover me</span>
</STooltip>
```

:::

::: details React

```tsx
<STooltip content="Tooltip content">
  <span>Hover me</span>
</STooltip>
```

:::

## Props

| Name | Description | Type | Default |
|------|-------------|------|---------|
| content | Tooltip content | `string` | - |
| placement | Tooltip position | `'top' \| 'bottom' \| 'left' \| 'right'` | `'top'` |
| trigger | Trigger mode | `'hover' \| 'click' \| 'focus'` | `'hover'` |