# Pagination

Page navigation component.

## Basic Usage

```vue
<SPagination
  :total="100"
  :pageSize="10"
  v-model="currentPage"
  @change="handleChange"
/>
```

## Props

| Name | Description | Type | Default |
|------|-------------|------|---------|
| modelValue | Current page | `number` | `1` |
| total | Total items | `number` | `0` |
| pageSize | Items per page | `number` | `10` |
| pageSizes | Page size options | `number[]` | `[10, 20, 50, 100]` |
| layout | Layout components | `string` | `'prev, pager, next'` |

## Events

| Name | Description |
|------|-------------|
| change | Triggered when page changes |
| sizeChange | Triggered when page size changes |