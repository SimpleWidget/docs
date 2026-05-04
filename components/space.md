# Space

Spacing component between elements.

## Basic Usage

::: tabs vue3 vue2 react
@tab vue3

```vue
<SSpace>
  <SButton>Button 1</SButton>
  <SButton>Button 2</SButton>
  <SInput placeholder="Input" />
</SSpace>
```

@tab vue2

```vue
<SSpace>
  <SButton>Button 1</SButton>
  <SButton>Button 2</SButton>
  <SInput placeholder="Input" />
</SSpace>
```

@tab react

```tsx
<SSpace>
  <SButton>Button 1</SButton>
  <SButton>Button 2</SButton>
  <SInput placeholder="Input" />
</SSpace>
```
:::

## Vertical

::: tabs vue3 vue2 react
@tab vue3

```vue
<SSpace direction="vertical">
  <SButton>Button 1</SButton>
  <SButton>Button 2</SButton>
  <SInput placeholder="Input" />
</SSpace>
```

@tab vue2

```vue
<SSpace direction="vertical">
  <SButton>Button 1</SButton>
  <SButton>Button 2</SButton>
  <SInput placeholder="Input" />
</SSpace>
```

@tab react

```tsx
<SSpace direction="vertical">
  <SButton>Button 1</SButton>
  <SButton>Button 2</SButton>
  <SInput placeholder="Input" />
</SSpace>
```
:::

## Props

### Vue3 / Vue2 / React

| Name | Description | Type | Default |
|------|-------------|------|---------|
| size | Space size | `'large' \| 'middle' \| 'small'` | `'middle'` |
| direction | Spacing direction | `'horizontal' \| 'vertical'` | `'horizontal'` |
| align | Alignment | `'start' \| 'center' \| 'end'` | - |