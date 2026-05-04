# Menu

Navigation menu component.

## Basic Usage

::: tabs vue3 vue2 react
@tab vue3

```vue
<SMenu :defaultActive="active" @select="handleSelect">
  <SMenuItem index="1">Menu Item 1</SMenuItem>
  <SMenuItem index="2">Menu Item 2</SMenuItem>
</SMenu>
```

@tab vue2

```vue
<SMenu :defaultActive="active" @select="handleSelect">
  <SMenuItem index="1">Menu Item 1</SMenuItem>
  <SMenuItem index="2">Menu Item 2</SMenuItem>
</SMenu>
```

@tab react

```tsx
<SMenu defaultActive={active} onSelect={handleSelect}>
  <SMenuItem index="1">Menu Item 1</SMenuItem>
  <SMenuItem index="2">Menu Item 2</SMenuItem>
</SMenu>
```
:::

## Horizontal Mode

::: tabs vue3 vue2 react
@tab vue3

```vue
<SMenu mode="horizontal">
  <SMenuItem index="1">Item 1</SMenuItem>
  <SMenuItem index="2">Item 2</SMenuItem>
</SMenu>
```

@tab vue2

```vue
<SMenu mode="horizontal">
  <SMenuItem index="1">Item 1</SMenuItem>
  <SMenuItem index="2">Item 2</SMenuItem>
</SMenu>
```

@tab react

```tsx
<SMenu mode="horizontal">
  <SMenuItem index="1">Item 1</SMenuItem>
  <SMenuItem index="2">Item 2</SMenuItem>
</SMenu>
```
:::

## Props

### Vue3 / Vue2 / React

| Name | Description | Type | Default |
|------|-------------|------|---------|
| defaultActive | Default active index | `string` | - |
| mode | Menu mode | `'horizontal' \| 'vertical'` | `'vertical'` |
| collapse | Collapsed state | `boolean` | `false` |

### MenuItem Props

| Name | Description | Type | Default |
|------|-------------|------|---------|
| index | Menu item index | `string` | - |
| disabled | Disabled state | `boolean` | `false` |

## Events

### Vue3 / Vue2

| Name | Description |
|------|-------------|
| select | Triggered when item selected |

### React

| Name | Description |
|------|-------------|
| onSelect | Triggered when item selected |