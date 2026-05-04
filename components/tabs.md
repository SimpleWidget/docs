# Tabs

Tab navigation component.

## Basic Usage

```vue
<STabs v-model="activeTab">
  <STabsItem label="Tab 1" name="tab1">Content 1</STabsItem>
  <STabsItem label="Tab 2" name="tab2">Content 2</STabsItem>
</STabs>
```

## Card Type

```vue
<STabs v-model="activeTab" type="card">
  <STabsItem label="Tab 1" name="tab1">Content 1</STabsItem>
  <STabsItem label="Tab 2" name="tab2">Content 2</STabsItem>
</STabs>
```

## Props

| Name | Description | Type | Default |
|------|-------------|------|---------|
| modelValue / v-model | Active tab name | `string` | - |
| type | Tab type | `'line' \| 'card'` | `'line'` |
| position | Tab position | `'top' \| 'bottom' \| 'left' \| 'right'` | `'top'` |

## TabsItem Props

| Name | Description | Type | Default |
|------|-------------|------|---------|
| label | Tab label | `string` | - |
| name | Tab identifier | `string` | - |
| disabled | Disabled state | `boolean` | `false` |

## Events

| Name | Description |
|------|-------------|
| change | Triggered when tab changes |

## React Props Difference

| Name | Description | Type | Default |
|------|-------------|------|---------|
| activeTab | Active tab name | `string` | - |
| onChange | Change handler | `(name: string) => void` | - |