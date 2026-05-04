# InfiniteScrolling

Infinite scroll component.

## Basic Usage

::: details Vue3

```vue
<SInfiniteScrolling @load="loadMore">
  <div v-for="item in list">{{ item }}</div>
</SInfiniteScrolling>
```

:::

::: details Vue2

```vue
<SInfiniteScrolling @load="loadMore">
  <div v-for="item in list">{{ item }}</div>
</SInfiniteScrolling>
```

:::

::: details React

```tsx
<SInfiniteScrolling onLoad={loadMore}>
  {list.map(item => <div key={item}>{item}</div>)}
</SInfiniteScrolling>
```

:::

## Props

| Name | Description | Type | Default |
|------|-------------|------|---------|
| distance | Load distance (px) | `number` | `100` |
| disabled | Disabled state | `boolean` | `false` |

## Events

| Name | Description | Vue3 | Vue2 | React |
|------|-------------|------|------|-------|
| load | Load more | `@load` | `@load` | `onLoad` |