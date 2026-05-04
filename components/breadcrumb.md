# Breadcrumb

Display navigation path.

## Basic Usage

::: details Vue3

```vue
<SBreadcrumb>
  <SBreadcrumbItem to="/">Home</SBreadcrumbItem>
  <SBreadcrumbItem to="/components">Components</SBreadcrumbItem>
  <SBreadcrumbItem>Breadcrumb</SBreadcrumbItem>
</SBreadcrumb>
```

:::

::: details Vue2

```vue
<SBreadcrumb>
  <SBreadcrumbItem to="/">Home</SBreadcrumbItem>
  <SBreadcrumbItem to="/components">Components</SBreadcrumbItem>
  <SBreadcrumbItem>Breadcrumb</SBreadcrumbItem>
</SBreadcrumb>
```

:::

::: details React

```tsx
<SBreadcrumb>
  <SBreadcrumbItem to="/">Home</SBreadcrumbItem>
  <SBreadcrumbItem to="/components">Components</SBreadcrumbItem>
  <SBreadcrumbItem>Breadcrumb</SBreadcrumbItem>
</SBreadcrumb>
```

:::

## Props

| Name | Description | Type | Default |
|------|-------------|------|---------|
| separator | Separator character | `string` | `'/'` |

### BreadcrumbItem Props

| Name | Description | Type | Default |
|------|-------------|------|---------|
| to | Link target | `string` | - |