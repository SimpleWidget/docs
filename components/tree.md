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

## With TreeNode

```vue
<STree :data="treeData">
  <STreeNode label="Parent">
    <STreeNode label="Child 1" />
    <STreeNode label="Child 2" />
  </STreeNode>
</STree>
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

## React Props Difference

| Name | Description | Type | Default |
|------|-------------|------|---------|
| onSelect | Selection handler | `(keys: string[]) => void` | - |
| onToggle | Toggle handler | `(key: string, expanded: boolean) => void` | - |