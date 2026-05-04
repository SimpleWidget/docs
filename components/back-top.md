# BackTop

Scroll back to top of page.

## Basic Usage

::: tabs vue3 vue2 react
@tab vue3

```vue
<SBackTop />
```

@tab vue2

```vue
<SBackTop />
```

@tab react

```tsx
<SBackTop />
```
:::

## Custom Content

::: tabs vue3 vue2 react
@tab vue3

```vue
<SBackTop>
  <div>Top</div>
</SBackTop>
```

@tab vue2

```vue
<SBackTop>
  <div>Top</div>
</SBackTop>
```

@tab react

```tsx
<SBackTop>
  <div>Top</div>
</SBackTop>
```
:::

## Props

### Vue3 / Vue2 / React

| Name | Description | Type | Default |
|------|-------------|------|---------|
| target | Scroll container selector | `string` | - |
| visibilityHeight | Show when scroll distance | `number` | `200` |
| duration | Scroll duration (ms) | `number` | `400` |