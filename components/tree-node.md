# TreeNode

Tree node component (used within STree).

## Basic Usage

```vue
<STree :data="treeData">
  <template #default="{ node }">
    <STreeNode :label="node.label" :children="node.children">
      <!-- Custom content -->
    </STreeNode>
  </template>
</STree>
```

## Props

| Name | Description | Type | Default |
|------|-------------|------|---------|
| label | Node label | `string` | - |
| children | Child nodes | `object[]` | - |
| disabled | Disabled state | `boolean` | `false` |

## Slots

| Name | Description |
|------|-------------|
| default | Custom node content |