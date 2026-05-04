# Card

Container for grouped content.

## Basic Usage

::: tabs vue3 vue2 react
@tab vue3

```vue
<SCard title="Card Title">
  <div>Card content</div>
</SCard>
```

@tab vue2

```vue
<SCard title="Card Title">
  <div>Card content</div>
</SCard>
```

@tab react

```tsx
<SCard title="Card Title">
  <div>Card content</div>
</SCard>
```
:::

## Shadow

::: tabs vue3 vue2 react
@tab vue3

```vue
<SCard title="Always Shadow" shadow="always">Always show shadow</SCard>
<SCard title="Hover Shadow" shadow="hover">Show shadow on hover</SCard>
<SCard title="No Shadow" shadow="never">No shadow</SCard>
```

@tab vue2

```vue
<SCard title="Always Shadow" shadow="always">Always show shadow</SCard>
<SCard title="Hover Shadow" shadow="hover">Show shadow on hover</SCard>
<SCard title="No Shadow" shadow="never">No shadow</SCard>
```

@tab react

```tsx
<SCard title="Always Shadow" shadow="always">Always show shadow</SCard>
<SCard title="Hover Shadow" shadow="hover">Show shadow on hover</SCard>
<SCard title="No Shadow" shadow="never">No shadow</SCard>
```
:::

## Props

### Vue3 / Vue2 / React

| Name | Description | Type | Default |
|------|-------------|------|---------|
| title | Card title | `string` | - |
| shadow | Shadow style | `'always' \| 'hover' \| 'never'` | `'always'` |
| bodyPadding | Body padding | `string` | `'20px'` |

## Slots

### Vue3 / Vue2

| Name | Description |
|------|-------------|
| default | Card content |
| header | Custom header |

### React

| Name | Description |
|------|-------------|
| children | Card content |
| header | Custom header |