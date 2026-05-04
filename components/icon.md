# Icon

Icon component.

## Basic Usage

::: tabs vue3 vue2 react
@tab vue3

```vue
<SIcon name="edit" />
<SIcon name="delete" size="20" color="#333" />
```

@tab vue2

```vue
<SIcon name="edit" />
<SIcon name="delete" size="20" color="#333" />
```

@tab react

```tsx
<SIcon name="edit" />
<SIcon name="delete" size={20} color="#333" />
```
:::

## Spin

::: tabs vue3 vue2 react
@tab vue3

```vue
<SIcon name="loading" spin />
```

@tab vue2

```vue
<SIcon name="loading" spin />
```

@tab react

```tsx
<SIcon name="loading" spin />
```
:::

## Props

### Vue3 / Vue2 / React

| Name | Description | Type | Default |
|------|-------------|------|---------|
| name | Icon name | `string` | - |
| size | Icon size | `string \| number` | `'16'` |
| color | Icon color | `string` | `'inherit'` |
| spin | Rotating animation | `boolean` | `false` |