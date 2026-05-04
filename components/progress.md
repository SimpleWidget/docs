# Progress

Progress indicator component.

## Basic Usage

::: details Vue3

```vue
<SProgress :percentage="50" />
<SProgress :percentage="80" type="circle" />
```

:::

::: details Vue2

```vue
<SProgress :percentage="50" />
<SProgress :percentage="80" type="circle" />
```

:::

::: details React

```tsx
<SProgress percentage={50} />
<SProgress percentage={80} type="circle" />
```

:::

## Props

| Name | Description | Type | Default |
|------|-------------|------|---------|
| percentage | Progress percentage | `number` | `0` |
| type | Progress type | `'line' \| 'circle' \| 'dashboard'` | `'line'` |
| strokeWidth | Stroke width | `number` | `6` |
| color | Progress color | `string` | - |