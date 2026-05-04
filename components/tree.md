# Tree

Tree structure component.

## Basic Usage

```vue
<STree
  :data="treeData"
  :expandedKeys="expandedKeys"
  @select="handleSelect"
  @toggle="handleToggle"
/>
```

## Props

| Name | Description | Type | Default |
|------|-------------|------|---------|
| data | Tree data | `object[]` | `[]` |
| expandedKeys | Expanded keys | `string[]` | `[]` |
| selectedKeys | Selected keys | `string[]` | `[]` |
| checkable | Show checkboxes | `boolean` | `false` |
| defaultExpandAll | Expand all by default | `boolean` | `false` |

## TreeNode Props

| Name | Description | Type | Default |
|------|-------------|------|---------|
| label | Node label | `string` | - |
| children | Child nodes | `object[]` | - |
| disabled | Disabled state | `boolean` | `false` |

## Events

| Name | Description |
|------|-------------|
| select | Triggered when node selected |
| toggle | Triggered when node expanded/collapsed |