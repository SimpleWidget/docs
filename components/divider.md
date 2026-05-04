# Divider

Content separator line.

## Basic Usage

::: tabs vue3 vue2 react
@tab vue3

```vue
<SDivider />
<SDivider direction="vertical" />
```

@tab vue2

```vue
<SDivider />
<SDivider direction="vertical" />
```

@tab react

```tsx
<SDivider />
<SDivider direction="vertical" />
```
:::

## With Content

::: tabs vue3 vue2 react
@tab vue3

```vue
<SDivider contentPosition="left">Text</SDivider>
<SDivider>Center</SDivider>
<SDivider contentPosition="right">Text</SDivider>
```

@tab vue2

```vue
<SDivider contentPosition="left">Text</SDivider>
<SDivider>Center</SDivider>
<SDivider contentPosition="right">Text</SDivider>
```

@tab react

```tsx
<SDivider contentPosition="left">Text</SDivider>
<SDivider>Center</SDivider>
<SDivider contentPosition="right">Text</SDivider>
```
:::

## Props

### Vue3 / Vue2 / React

| Name | Description | Type | Default |
|------|-------------|------|---------|
| direction | Separator direction | `'horizontal' \| 'vertical'` | `'horizontal'` |
| contentPosition | Content position | `'left' \| 'center' \| 'right'` | `'center'` |
| borderStyle | Border style | `string` | `'solid'` |