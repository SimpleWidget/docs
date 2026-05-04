# Icon

Icon component.

## Basic Usage

::: details Vue3

```vue
<SIcon name="edit" />
<SIcon name="delete" size="20" color="#333" />
```

:::

::: details Vue2

```vue
<SIcon name="edit" />
<SIcon name="delete" size="20" color="#333" />
```

:::

::: details React

```tsx
<SIcon name="edit" />
<SIcon name="delete" size={20} color="#333" />
```

:::

## Props

| Name | Description | Type | Default |
|------|-------------|------|---------|
| name | Icon name | `string` | - |
| size | Icon size | `string \| number` | `'16'` |
| color | Icon color | `string` | `'inherit'` |
| spin | Rotating animation | `boolean` | `false` |