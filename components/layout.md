# Layout

Layout container component.

## Basic Usage

```vue
<SLayout>
  <SLayout.Sider>Sider</SLayout.Sider>
  <SLayout>
    <SLayout.Header>Header</SLayout.Header>
    <SLayout.Content>Content</SLayout.Content>
    <SLayout.Footer>Footer</SLayout.Footer>
  </SLayout>
</SLayout>
```

## Props

| Name | Description | Type | Default |
|------|-------------|------|---------|
| direction | Direction | `'vertical' \| 'horizontal'` | `'horizontal'` |

## Sider Props

| Name | Description | Type | Default |
|------|-------------|------|---------|
| width | Sider width | `string` | `'200px'` |
| collapsible | Collapsible | `boolean` | `false` |