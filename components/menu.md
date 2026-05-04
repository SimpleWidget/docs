# Menu

Navigation menu component.

## Basic Usage

::: details Vue3

```vue
<SMenu :defaultActive="active" @select="handleSelect">
  <SMenuItem index="1">Menu Item 1</SMenuItem>
  <SMenuItem index="2">Menu Item 2</SMenuItem>
</SMenu>
```

:::

::: details Vue2

```vue
<SMenu :defaultActive="active" @select="handleSelect">
  <SMenuItem index="1">Menu Item 1</SMenuItem>
  <SMenuItem index="2">Menu Item 2</SMenuItem>
</SMenu>
```

:::

::: details React

```tsx
<SMenu defaultActive={active} onSelect={handleSelect}>
  <SMenuItem index="1">Menu Item 1</SMenuItem>
  <SMenuItem index="2">Menu Item 2</SMenuItem>
</SMenu>
```

:::

## Props

| Name | Description | Type | Default |
|------|-------------|------|---------|
| defaultActive | Default active index | `string` | - |
| mode | Menu mode | `'horizontal' \| 'vertical'` | `'vertical'` |

## Events

| Name | Description | Vue3 | Vue2 | React |
|------|-------------|------|------|-------|
| select | Item selection | `@select` | `@select` | `onSelect` |