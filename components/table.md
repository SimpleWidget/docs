# Table

Data table component.

## Basic Usage

::: details Vue3

```vue
<STable
  :data="tableData"
  :columns="columns"
  @select="handleSelect"
  @rowClick="handleRowClick"
/>
```

:::

::: details Vue2

```vue
<STable
  :data="tableData"
  :columns="columns"
  @select="handleSelect"
  @rowClick="handleRowClick"
/>
```

:::

::: details React

```tsx
<STable
  data={tableData}
  columns={columns}
  onSelect={handleSelect}
  onRowClick={handleRowClick}
/>
```

:::

## With Selection

::: details Vue3

```vue
<STable :data="tableData" :columns="columns" select />
```

:::

::: details Vue2

```vue
<STable :data="tableData" :columns="columns" select />
```

:::

::: details React

```tsx
<STable data={tableData} columns={columns} select />
```

:::

## Props

| Name | Description | Type | Default |
|------|-------------|------|---------|
| data | Table data array | `object[]` | `[]` |
| columns | Column definitions | `object[]` | `[]` |
| align | Table alignment | `'left' \| 'center' \| 'right'` | `'left'` |
| border | Show border | `boolean` | `false` |
| stripe | Show stripe | `boolean` | `false` |
| select | Enable selection | `boolean` | `false` |
| num | Show row number | `boolean` | `false` |

## Column Props

| Name | Description | Type | Default |
|------|-------------|------|---------|
| prop | Data property | `string` | - |
| label | Column label | `string` | - |
| width | Column width | `string` | - |

## Events

| Name | Description | Vue3 | Vue2 | React |
|------|-------------|------|------|-------|
| select | Row selection | `@select` | `@select` | `onSelect` |
| rowClick | Row click | `@rowClick` | `@rowClick` | `onRowClick` |