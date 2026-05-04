# Tree

Tree structure component.

## Basic Usage

::: tabs vue3 vue2 react
@tab vue3

```vue
<STree
  :data="treeData"
  :expandedKeys="expandedKeys"
  @select="handleSelect"
  @toggle="handleToggle"
/>
```

@tab vue2

```vue
<STree
  :data="treeData"
  :expandedKeys="expandedKeys"
  @select="handleSelect"
  @toggle="handleToggle"
/>
```

@tab react

```tsx
<STree
  data={treeData}
  expandedKeys={expandedKeys}
  onSelect={handleSelect}
  onToggle={handleToggle}
/>
```
:::

## With TreeNode

::: tabs vue3 vue2 react
@tab vue3

```vue
<STree :data="treeData">
  <STreeNode label="Parent">
    <STreeNode label="Child 1" />
    <STreeNode label="Child 2" />
  </STreeNode>
</STree>
```

@tab vue2

```vue
<STree :data="treeData">
  <STreeNode label="Parent">
    <STreeNode label="Child 1" />
    <STreeNode label="Child 2" />
  </STreeNode>
</STree>
```

@tab react

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

### Vue3 / Vue2 / React

| Name | Description | Type | Default |
|------|-------------|------|---------|
| data | Tree data | `object[]` | `[]` |
| expandedKeys | Expanded keys | `string[]` | `[]` |
| selectedKeys | Selected keys | `string[]` | `[]` |
| checkable | Show checkboxes | `boolean` | `false` |
| defaultExpandAll | Expand all by default | `boolean` | `false` |

### TreeNode Props

| Name | Description | Type | Default |
|------|-------------|------|---------|
| label | Node label | `string` | - |
| children | Child nodes | `object[]` | - |
| disabled | Disabled state | `boolean` | `false` |

## Events

### Vue3 / Vue2

| Name | Description |
|------|-------------|
| select | Triggered when node selected |
| toggle | Triggered when node expanded/collapsed |

### React

| Name | Description |
|------|-------------|
| onSelect | Triggered when node selected |
| onToggle | Triggered when node expanded/collapsed |