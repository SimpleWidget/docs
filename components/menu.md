# Menu

Navigation menu component.

## Basic Usage

```vue
<SMenu :defaultActive="active" @select="handleSelect">
  <SMenuItem index="1">Menu Item 1</SMenuItem>
  <SMenuItem index="2">Menu Item 2</SMenuItem>
</SMenu>
```

## Props

| Name | Description | Type | Default |
|------|-------------|------|---------|
| defaultActive | Default active index | `string` | - |
| mode | Menu mode | `'horizontal' \| 'vertical'` | `'vertical'` |
| collapse | Collapsed state | `boolean` | `false` |

## MenuItem Props

| Name | Description | Type | Default |
|------|-------------|------|---------|
| index | Menu item index | `string` | - |
| disabled | Disabled state | `boolean` | `false` |

## Events

| Name | Description |
|------|-------------|
| select | Triggered when item selected |