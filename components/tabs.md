# Tabs

Tab navigation component.

## Basic Usage

::: tabs vue3 vue2 react
@tab vue3

```vue
<STabs v-model="activeTab">
  <STabsItem label="Tab 1" name="tab1">Content 1</STabsItem>
  <STabsItem label="Tab 2" name="tab2">Content 2</STabsItem>
</STabs>
```

@tab vue2

```vue
<STabs v-model="activeTab">
  <STabsItem label="Tab 1" name="tab1">Content 1</STabsItem>
  <STabsItem label="Tab 2" name="tab2">Content 2</STabsItem>
</STabs>
```

@tab react

```tsx
<STabs activeTab={activeTab} onChange={setActiveTab}>
  <STabsItem label="Tab 1" name="tab1">Content 1</STabsItem>
  <STabsItem label="Tab 2" name="tab2">Content 2</STabsItem>
</STabs>
```
:::

## Card Type

::: tabs vue3 vue2 react
@tab vue3

```vue
<STabs v-model="activeTab" type="card">
  <STabsItem label="Tab 1" name="tab1">Content 1</STabsItem>
  <STabsItem label="Tab 2" name="tab2">Content 2</STabsItem>
</STabs>
```

@tab vue2

```vue
<STabs v-model="activeTab" type="card">
  <STabsItem label="Tab 1" name="tab1">Content 1</STabsItem>
  <STabsItem label="Tab 2" name="tab2">Content 2</STabsItem>
</STabs>
```

@tab react

```tsx
<STabs activeTab={activeTab} onChange={setActiveTab} type="card">
  <STabsItem label="Tab 1" name="tab1">Content 1</STabsItem>
  <STabsItem label="Tab 2" name="tab2">Content 2</STabsItem>
</STabs>
```
:::

## Props

### Vue3 / Vue2 / React

| Name | Description | Type | Default |
|------|-------------|------|---------|
| modelValue / v-model / activeTab | Active tab name | `string` | - |
| type | Tab type | `'line' \| 'card'` | `'line'` |
| position | Tab position | `'top' \| 'bottom' \| 'left' \| 'right'` | `'top'` |

### TabsItem Props

| Name | Description | Type | Default |
|------|-------------|------|---------|
| label | Tab label | `string` | - |
| name | Tab identifier | `string` | - |
| disabled | Disabled state | `boolean` | `false` |

## Events

### Vue3 / Vue2

| Name | Description |
|------|-------------|
| change | Triggered when tab changes |

### React

| Name | Description |
|------|-------------|
| onChange | Triggered when tab changes |