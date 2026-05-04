# InfiniteScrolling

Infinite scroll component.

## Basic Usage

```vue
<SInfiniteScrolling @load="loadMore">
  <div v-for="item in list">{{ item }}</div>
</SInfiniteScrolling>
```

## Props

| Name | Description | Type | Default |
|------|-------------|------|---------|
| distance | Load distance (px) | `number` | `100` |
| disabled | Disabled state | `boolean` | `false` |
| immediate | Immediate check | `boolean` | `true` |

## Events

| Name | Description |
|------|-------------|
| load | Triggered when scroll to bottom |