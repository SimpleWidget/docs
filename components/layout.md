# Layout

Layout container component.

## Basic Usage

::: tabs vue3 vue2 react
@tab vue3

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

@tab vue2

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

@tab react

```tsx
<SLayout>
  <SLayout.Sider>Sider</SLayout.Sider>
  <SLayout>
    <SLayout.Header>Header</SLayout.Header>
    <SLayout.Content>Content</SLayout.Content>
    <SLayout.Footer>Footer</SLayout.Footer>
  </SLayout>
</SLayout>
```
:::

## Layout Props

### Vue3 / Vue2 / React

| Name | Description | Type | Default |
|------|-------------|------|---------|
| direction | Direction | `'vertical' \| 'horizontal'` | `'horizontal'` |

## Sider Props

| Name | Description | Type | Default |
|------|-------------|------|---------|
| width | Sider width | `string` | `'200px'` |
| collapsible | Collapsible | `boolean` | `false` |