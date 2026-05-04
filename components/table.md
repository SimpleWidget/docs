# Table

Data table component.

## Basic Usage

::: tabs vue3 vue2 react
@tab vue3

```vue
<STable
  :data="tableData"
  :columns="columns"
  @select="handleSelect"
  @rowClick="handleRowClick"
/>
```

@tab vue2

```vue
<STable
  :data="tableData"
  :columns="columns"
  @select="handleSelect"
  @rowClick="handleRowClick"
/>
```

@tab react

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

::: tabs vue3 vue2 react
@tab vue3

```vue
<STable :data="tableData" :columns="columns" select @select="handleSelect" />
```

@tab vue2

```vue
<STable :data="tableData" :columns="columns" select @select="handleSelect" />
```

@tab react

```tsx
<STable data={tableData} columns={columns} select onSelect={handleSelect} />
```
:::

## With Row Numbers

::: tabs vue3 vue2 react
@tab vue3

```vue
<STable :data="tableData" :columns="columns" num />
```

@tab vue2

```vue
<STable :data="tableData" :columns="columns" num />
```

@tab react

```tsx
<STable data={tableData} columns={columns} num />
```
:::

## Props

### Vue3 / Vue2 / React

| Name | Description | Type | Default |
|------|-------------|------|---------|
| data | Table data array | `object[]` | `[]` |
| columns | Column definitions | `object[]` | `[]` |
| align | Table alignment | `'left' \| 'center' \| 'right'` | `'left'` |
| border | Show border | `boolean` | `false` |
| stripe | Show stripe | `boolean` | `false` |
| hover | Show hover effect | `boolean` | `true` |
| select | Enable selection | `boolean` | `false` |
| num | Show row number | `boolean` | `false` |
| height | Fixed height | `string` | - |
| maxHeight | Maximum height | `string` | - |

## Column Props

| Name | Description | Type | Default |
|------|-------------|------|---------|
| prop | Data property | `string` | - |
| label | Column label | `string` | - |
| width | Column width | `string` | - |
| fixed | Fixed column | `'left' \| 'right'` | - |

## Events

### Vue3 / Vue2

| Name | Description |
|------|-------------|
| select | Triggered when row selected |
| rowClick | Triggered when row clicked |

### React

| Name | Description |
|------|-------------|
| onSelect | Triggered when row selected |
| onRowClick | Triggered when row clicked |