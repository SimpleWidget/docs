# Badge

Badge is used to display status or count.

## Basic Usage

::: details Vue3

```vue
<SBadge value="5">
  <div class="box">Content</div>
</SBadge>
<SBadge value="99" />
<SBadge value="100" :max="99" />
```

:::

::: details Vue2

```vue
<SBadge value="5">
  <div class="box">Content</div>
</SBadge>
<SBadge value="99" />
<SBadge :value="100" :max="99" />
```

:::

::: details React

```tsx
<SBadge value="5">
  <div className="box">Content</div>
</SBadge>
<SBadge value="99" />
<SBadge value={100} max={99} />
```

:::

## Props

| Name | Description | Type | Default |
|------|-------------|------|---------|
| value | Badge value | `string \| number` | `''` |
| type | Badge type | `'primary' \| 'success' \| 'danger' \| 'warning' \| 'info'` | `'danger'` |
| max | Max value | `number` | `99` |
| dot | Dot mode | `boolean` | `false` |
| show | Show/hide | `boolean` | `true` |