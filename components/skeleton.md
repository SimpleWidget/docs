# Skeleton

Loading skeleton component.

## Basic Usage

::: tabs vue3 vue2 react
@tab vue3

```vue
<SSkeleton :rows="5" animated />
```

@tab vue2

```vue
<SSkeleton :rows="5" animated />
```

@tab react

```tsx
<SSkeleton rows={5} animated />
```
:::

## Props

### Vue3 / Vue2 / React

| Name | Description | Type | Default |
|------|-------------|------|---------|
| rows | Number of skeleton rows | `number` | `3` |
| animated | Show animation | `boolean` | `true` |
| variant | Skeleton variant | `'text' \| 'circular' \| 'rect'` | `'text'` |