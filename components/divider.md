# Divider

Content separator line.

## Basic Usage

```vue
<SDivider />
<SDivider direction="vertical" />
```

## With Content

```vue
<SDivider contentPosition="left">Text</SDivider>
<SDivider>Center</SDivider>
<SDivider contentPosition="right">Text</SDivider>
```

## Props

| Name | Description | Type | Default |
|------|-------------|------|---------|
| direction | Separator direction | `'horizontal' \| 'vertical'` | `'horizontal'` |
| contentPosition | Content position | `'left' \| 'center' \| 'right'` | `'center'` |
| borderStyle | Border style | `string` | `'solid'` |