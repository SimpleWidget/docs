# Pagination

Page navigation component.

## Basic Usage

::: details Vue3

```vue
<SPagination
  :total="100"
  v-model="currentPage"
  @change="handleChange"
/>
```

:::

::: details Vue2

```vue
<SPagination
  :total="100"
  v-model="currentPage"
  @change="handleChange"
/>
```

:::

::: details React

```tsx
<SPagination
  total={100}
  currentPage={currentPage}
  onChange={handleChange}
/>
```

:::

## Props

| Name | Description | Type | Default |
|------|-------------|------|---------|
| modelValue / v-model / currentPage | Current page | `number` | `1` |
| total | Total items | `number` | `0` |
| pageSize | Items per page | `number` | `10` |
| pageSizes | Page size options | `number[]` | `[10, 20, 50, 100]` |

## Events

| Name | Description | Vue3 | Vue2 | React |
|------|-------------|------|------|-------|
| change | Page change | `@change` | `@change` | `onChange` |
| sizeChange | Size change | `@sizeChange` | `@sizeChange` | `onSizeChange` |