# TreeNode

Tree node component (used within STree).

## Basic Usage

::: details Vue3

```vue
<STree :data="treeData">
  <STreeNode label="Parent">
    <STreeNode label="Child 1" />
    <STreeNode label="Child 2" />
  </STreeNode>
</STree>
```

:::

::: details Vue2

```vue
<STree :data="treeData">
  <STreeNode label="Parent">
    <STreeNode label="Child 1" />
    <STreeNode label="Child 2" />
  </STreeNode>
</STree>
```

:::

::: details React

```tsx
<STree data={treeData}>
  <STreeNode label="Parent">
    <STreeNode label="Child 1" />
    <STreeNode label="Child 2" />
  </STreeNode>
</STree>
```

:::

## Props

| Name | Description | Type | Default |
|------|-------------|------|---------|
| label | Node label | `string` | - |
| children | Child nodes | `object[]` | - |
| disabled | Disabled state | `boolean` | `false` |