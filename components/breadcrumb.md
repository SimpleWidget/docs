# Breadcrumb

Display navigation path.

## Basic Usage

```vue
<SBreadcrumb>
  <SBreadcrumbItem to="/">Home</SBreadcrumbItem>
  <SBreadcrumbItem to="/components">Components</SBreadcrumbItem>
  <SBreadcrumbItem>Breadcrumb</SBreadcrumbItem>
</SBreadcrumb>
```

## Custom Separator

```vue
<SBreadcrumb separator=">">
  <SBreadcrumbItem to="/">Home</SBreadcrumbItem>
  <SBreadcrumbItem>Current</SBreadcrumbItem>
</SBreadcrumb>
```

## Props

| Name | Description | Type | Default |
|------|-------------|------|---------|
| separator | Separator character | `string` | `'/'` |

### BreadcrumbItem Props

| Name | Description | Type | Default |
|------|-------------|------|---------|
| to | Link target | `string` | - |
| replace | Replace history | `boolean` | `false` |