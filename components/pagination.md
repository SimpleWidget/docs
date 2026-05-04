# Pagination

Page navigation component.

## Basic Usage

::: tabs vue3 vue2 react
@tab vue3

```vue
<SPagination
  :total="100"
  :pageSize="10"
  v-model="currentPage"
  @change="handleChange"
/>
```

@tab vue2

```vue
<SPagination
  :total="100"
  :pageSize="10"
  v-model="currentPage"
  @change="handleChange"
/>
```

@tab react

```tsx
<SPagination
  total={100}
  pageSize={10}
  currentPage={currentPage}
  onChange={handleChange}
/>
```
:::

## With Page Sizes

::: tabs vue3 vue2 react
@tab vue3

```vue
<SPagination
  :total="100"
  :pageSizes="[10, 20, 50, 100]"
  v-model="currentPage"
/>
```

@tab vue2

```vue
<SPagination
  :total="100"
  :pageSizes="[10, 20, 50, 100]"
  v-model="currentPage"
/>
```

@tab react

```tsx
<SPagination
  total={100}
  pageSizes={[10, 20, 50, 100]}
  currentPage={currentPage}
  onChange={handleChange}
/>
```
:::

## Props

### Vue3 / Vue2 / React

| Name | Description | Type | Default |
|------|-------------|------|---------|
| modelValue / v-model / currentPage | Current page | `number` | `1` |
| total | Total items | `number` | `0` |
| pageSize | Items per page | `number` | `10` |
| pageSizes | Page size options | `number[]` | `[10, 20, 50, 100]` |
| layout | Layout components | `string` | `'prev, pager, next'` |

## Events

### Vue3 / Vue2

| Name | Description |
|------|-------------|
| change | Triggered when page changes |
| sizeChange | Triggered when page size changes |

### React

| Name | Description |
|------|-------------|
| onChange | Triggered when page changes |
| onSizeChange | Triggered when page size changes |