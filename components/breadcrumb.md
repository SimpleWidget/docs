# Breadcrumb

Display navigation path.

## Basic Usage

::: tabs vue3 vue2 react
@tab vue3

```vue
<SBreadcrumb>
  <SBreadcrumbItem to="/">Home</SBreadcrumbItem>
  <SBreadcrumbItem to="/components">Components</SBreadcrumbItem>
  <SBreadcrumbItem>Breadcrumb</SBreadcrumbItem>
</SBreadcrumb>
```

@tab vue2

```vue
<SBreadcrumb>
  <SBreadcrumbItem to="/">Home</SBreadcrumbItem>
  <SBreadcrumbItem to="/components">Components</SBreadcrumbItem>
  <SBreadcrumbItem>Breadcrumb</SBreadcrumbItem>
</SBreadcrumb>
```

@tab react

```tsx
<SBreadcrumb>
  <SBreadcrumbItem to="/">Home</SBreadcrumbItem>
  <SBreadcrumbItem to="/components">Components</SBreadcrumbItem>
  <SBreadcrumbItem>Breadcrumb</SBreadcrumbItem>
</SBreadcrumb>
```
:::

## Custom Separator

::: tabs vue3 vue2 react
@tab vue3

```vue
<SBreadcrumb separator=">">
  <SBreadcrumbItem to="/">Home</SBreadcrumbItem>
  <SBreadcrumbItem>Current</SBreadcrumbItem>
</SBreadcrumb>
```

@tab vue2

```vue
<SBreadcrumb separator=">">
  <SBreadcrumbItem to="/">Home</SBreadcrumbItem>
  <SBreadcrumbItem>Current</SBreadcrumbItem>
</SBreadcrumb>
```

@tab react

```tsx
<SBreadcrumb separator=">">
  <SBreadcrumbItem to="/">Home</SBreadcrumbItem>
  <SBreadcrumbItem>Current</SBreadcrumbItem>
</SBreadcrumb>
```
:::

## Props

### Vue3 / Vue2 / React

| Name | Description | Type | Default |
|------|-------------|------|---------|
| separator | Separator character | `string` | `'/'` |

### BreadcrumbItem Props

| Name | Description | Type | Default |
|------|-------------|------|---------|
| to | Link target | `string` | - |
| replace | Replace history | `boolean` | `false` |