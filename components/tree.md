# Tree

Tree structure component.

## Basic Usage

::: details Vue3

```vue
<STree
  :data="treeData"
  :expandedKeys="expandedKeys"
  @select="handleSelect"
  @toggle="handleToggle"
/>
```

:::

::: details Vue2

```vue
<STree
  :data="treeData"
  :expandedKeys="expandedKeys"
  @select="handleSelect"
  @toggle="handleToggle"
/>
```

:::

::: details React

```tsx
<STree
  data={treeData}
  expandedKeys={expandedKeys}
  onSelect={handleSelect}
  onToggle={handleToggle}
/>
```

:::

## Props

| Name | Description | Type | Default |
|------|-------------|------|---------|
| data | Tree data | `object[]` | `[]` |
| expandedKeys | Expanded keys | `string[]` | `[]` |
| checkable | Show checkboxes | `boolean` | `false` |

## Events

| Name | Description | Vue3 | Vue2 | React |
|------|-------------|------|------|-------|
| select | Node selection | `@select` | `@select` | `onSelect` |
| toggle | Expand/collapse | `@toggle` | `@toggle` | `onToggle` |