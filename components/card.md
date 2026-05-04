# Card

Container for grouped content.

## Basic Usage

```vue
<SCard title="Card Title">
  <div>Card content</div>
</SCard>
```

## Shadow

```vue
<SCard title="Always Shadow" shadow="always">Always show shadow</SCard>
<SCard title="Hover Shadow" shadow="hover">Show shadow on hover</SCard>
<SCard title="No Shadow" shadow="never">No shadow</SCard>
```

## Props

| Name | Description | Type | Default |
|------|-------------|------|---------|
| title | Card title | `string` | - |
| shadow | Shadow style | `'always' \| 'hover' \| 'never'` | `'always'` |
| bodyPadding | Body padding | `string` | `'20px'` |

## Slots

| Name | Description |
|------|-------------|
| default | Card content |
| header | Custom header |