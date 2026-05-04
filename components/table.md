# Table

Data table component.

## Basic Usage

```vue
<STable
  :data="tableData"
  :columns="columns"
  @select="handleSelect"
  @rowClick="handleRowClick"
/>
```

## Props

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

| Name | Description |
|------|-------------|
| select | Triggered when row selected |
| rowClick | Triggered when row clicked |