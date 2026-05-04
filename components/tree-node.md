# TreeNode

Tree node component (used within STree).

## Basic Usage

::: tabs vue3 vue2 react
@tab vue3

```vue
<STree :data="treeData">
  <template #default="{ node }">
    <STreeNode :label="node.label" :children="node.children">
      <!-- Custom content -->
    </STreeNode>
  </template>
</STree>
```

@tab vue2

```vue
<STree :data="treeData">
  <template slot-scope="{ node }">
    <STreeNode :label="node.label" :children="node.children">
      <!-- Custom content -->
    </STreeNode>
  </template>
</STree>
```

@tab react

```tsx
<STree data={treeData}>
  {(node) => (
    <STreeNode label={node.label} children={node.children}>
      {/* Custom content */}
    </STreeNode>
  )}
</STree>
```
:::

## Props

### Vue3 / Vue2 / React

| Name | Description | Type | Default |
|------|-------------|------|---------|
| label | Node label | `string` | - |
| children | Child nodes | `object[]` | - |
| disabled | Disabled state | `boolean` | `false` |