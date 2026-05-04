# Loading

Loading state component.

## Basic Usage

::: details Vue3

```vue
<SLoading v-model="loading" />
<div v-loading="loading">Content</div>
```

:::

::: details Vue2

```vue
<SLoading v-model="loading" />
<div v-loading="loading">Content</div>
```

:::

::: details React

```tsx
<SLoading loading={loading} />
<div className={loading ? 'loading' : ''}>Content</div>
```

:::

## Fullscreen

::: details Vue3

```vue
<SLoading fullscreen />
```

:::

::: details Vue2

```vue
<SLoading fullscreen />
```

:::

::: details React

```tsx
<SLoading fullscreen />
```

:::

## Props

| Name | Description | Type | Default |
|------|-------------|------|---------|
| modelValue / v-model / loading | Loading state | `boolean` | `false` |
| text | Loading text | `string` | `'Loading...'` |
| fullscreen | Full screen loading | `boolean` | `false` |