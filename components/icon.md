# Icon

Icon component.

## Basic Usage

```vue
<SIcon name="edit" />
<SIcon name="delete" size="20" color="#333" />
```

## Spin

```vue
<SIcon name="loading" spin />
```

## Props

| Name | Description | Type | Default |
|------|-------------|------|---------|
| name | Icon name | `string` | - |
| size | Icon size | `string \| number` | `'16'` |
| color | Icon color | `string` | `'inherit'` |
| spin | Rotating animation | `boolean` | `false` |