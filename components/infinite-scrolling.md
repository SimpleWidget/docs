# InfiniteScrolling

Infinite scroll component.

## Basic Usage

::: tabs vue3 vue2 react
@tab vue3

```vue
<SInfiniteScrolling @load="loadMore">
  <div v-for="item in list">{{ item }}</div>
</SInfiniteScrolling>
```

@tab vue2

```vue
<SInfiniteScrolling @load="loadMore">
  <div v-for="item in list">{{ item }}</div>
</SInfiniteScrolling>
```

@tab react

```tsx
<SInfiniteScrolling onLoad={loadMore}>
  {list.map(item => <div key={item}>{item}</div>)}
</SInfiniteScrolling>
```
:::

## Props

### Vue3 / Vue2 / React

| Name | Description | Type | Default |
|------|-------------|------|---------|
| distance | Load distance (px) | `number` | `100` |
| disabled | Disabled state | `boolean` | `false` |
| immediate | Immediate check | `boolean` | `true` |

## Events

### Vue3 / Vue2

| Name | Description |
|------|-------------|
| load | Triggered when scroll to bottom |

### React

| Name | Description |
|------|-------------|
| onLoad | Triggered when scroll to bottom |