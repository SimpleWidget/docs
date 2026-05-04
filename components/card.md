# Card

Container for grouped content.

## Basic Usage

::: details Vue3

```vue
<SCard title="Card Title">
  <div>Card content</div>
</SCard>
```

:::

::: details Vue2

```vue
<SCard title="Card Title">
  <div>Card content</div>
</SCard>
```

:::

::: details React

```tsx
<SCard title="Card Title">
  <div>Card content</div>
</SCard>
```

:::

## Props

| Name | Description | Type | Default |
|------|-------------|------|---------|
| title | Card title | `string` | - |
| shadow | Shadow style | `'always' \| 'hover' \| 'never'` | `'always'` |
| bodyPadding | Body padding | `string` | `'20px'` |

## Slots

| Name | Vue3 | Vue2 | React |
|------|------|------|-------|
| default | `#default` | `slot="default"` | children |
| header | `#header` | `slot="header"` | header prop |