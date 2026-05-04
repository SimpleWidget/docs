# Card

Container for grouped content.

## Basic Usage

```vue
<SCard title="Card Title">
  <div>Card content</div>
</SCard>
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