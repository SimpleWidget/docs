# Empty

Empty state display.

## Basic Usage

::: tabs vue3 vue2 react
@tab vue3

```vue
<SEmpty description="No data" />
```

@tab vue2

```vue
<SEmpty description="No data" />
```

@tab react

```tsx
<SEmpty description="No data" />
```
:::

## Custom Image

::: tabs vue3 vue2 react
@tab vue3

```vue
<SEmpty image="/empty.png" description="Nothing here" />
```

@tab vue2

```vue
<SEmpty image="/empty.png" description="Nothing here" />
```

@tab react

```tsx
<SEmpty image="/empty.png" description="Nothing here" />
```
:::

## Props

### Vue3 / Vue2 / React

| Name | Description | Type | Default |
|------|-------------|------|---------|
| image | Custom image URL | `string` | - |
| description | Description text | `string` | `'No data'` |
| imageSize | Image size | `number` | - |