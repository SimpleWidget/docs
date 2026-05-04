# Space

Spacing component between elements.

## Basic Usage

```vue
<SSpace>
  <SButton>Button 1</SButton>
  <SButton>Button 2</SButton>
  <SInput placeholder="Input" />
</SSpace>
```

## Vertical

```vue
<SSpace direction="vertical">
  <SButton>Button 1</SButton>
  <SButton>Button 2</SButton>
  <SInput placeholder="Input" />
</SSpace>
```

## Props

| Name | Description | Type | Default |
|------|-------------|------|---------|
| size | Space size | `'large' \| 'middle' \| 'small'` | `'middle'` |
| direction | Spacing direction | `'horizontal' \| 'vertical'` | `'horizontal'` |
| align | Alignment | `'start' \| 'center' \| 'end'` | - |