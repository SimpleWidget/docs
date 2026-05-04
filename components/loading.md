# Loading

Loading state component.

## Basic Usage

::: tabs vue3 vue2 react
@tab vue3

```vue
<SLoading v-model="loading" />
<div v-loading="loading">Content</div>
```

@tab vue2

```vue
<SLoading v-model="loading" />
<div v-loading="loading">Content</div>
```

@tab react

```tsx
<SLoading loading={loading} text="Loading..." />
<div className="loading-overlay">Content</div>
```
:::

## Fullscreen

::: tabs vue3 vue2 react
@tab vue3

```vue
<SLoading fullscreen />
```

@tab vue2

```vue
<SLoading fullscreen />
```

@tab react

```tsx
<SLoading fullscreen />
```
:::

## Props

### Vue3 / Vue2 / React

| Name | Description | Type | Default |
|------|-------------|------|---------|
| modelValue / v-model / loading | Loading state | `boolean` | `false` |
| text | Loading text | `string` | `'Loading...'` |
| fullscreen | Full screen loading | `boolean` | `false` |
| background | Mask background | `string` | `'rgba(0,0,0,0.7)'` |