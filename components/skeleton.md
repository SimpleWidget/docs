# Skeleton

Loading skeleton component.

## Basic Usage

::: details Vue3

```vue
<SSkeleton :rows="5" animated />
```

:::

::: details Vue2

```vue
<SSkeleton :rows="5" animated />
```

:::

::: details React

```tsx
<SSkeleton rows={5} animated />
```

:::

## Props

| Name | Description | Type | Default |
|------|-------------|------|---------|
| rows | Number of skeleton rows | `number` | `3` |
| animated | Show animation | `boolean` | `true` |
| variant | Skeleton variant | `'text' \| 'circular' \| 'rect'` | `'text'` |