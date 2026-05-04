# Tooltip

Tooltip information component.

## Basic Usage

::: tabs vue3 vue2 react
@tab vue3

```vue
<STooltip content="Tooltip content">
  <span>Hover me</span>
</STooltip>
```

@tab vue2

```vue
<STooltip content="Tooltip content">
  <span>Hover me</span>
</STooltip>
```

@tab react

```tsx
<STooltip content="Tooltip content">
  <span>Hover me</span>
</STooltip>
```
:::

## Positions

::: tabs vue3 vue2 react
@tab vue3

```vue
<STooltip content="Top" placement="top">Top</STooltip>
<STooltip content="Bottom" placement="bottom">Bottom</STooltip>
<STooltip content="Left" placement="left">Left</STooltip>
<STooltip content="Right" placement="right">Right</STooltip>
```

@tab vue2

```vue
<STooltip content="Top" placement="top">Top</STooltip>
<STooltip content="Bottom" placement="bottom">Bottom</STooltip>
<STooltip content="Left" placement="left">Left</STooltip>
<STooltip content="Right" placement="right">Right</STooltip>
```

@tab react

```tsx
<STooltip content="Top" placement="top">Top</STooltip>
<STooltip content="Bottom" placement="bottom">Bottom</STooltip>
<STooltip content="Left" placement="left">Left</STooltip>
<STooltip content="Right" placement="right">Right</STooltip>
```
:::

## Props

### Vue3 / Vue2 / React

| Name | Description | Type | Default |
|------|-------------|------|---------|
| content | Tooltip content | `string` | - |
| placement | Tooltip position | `'top' \| 'bottom' \| 'left' \| 'right'` | `'top'` |
| trigger | Trigger mode | `'hover' \| 'click' \| 'focus'` | `'hover'` |
| delay | Show delay (ms) | `number` | `0` |