# Button

Buttons are used to trigger actions.

## Basic Usage

```vue
<SButton type="primary">Primary</SButton>
<SButton type="success">Success</SButton>
<SButton type="danger">Danger</SButton>
<SButton type="warning">Warning</SButton>
<SButton type="info">Info</SButton>
<SButton type="default">Default</SButton>
```

## Sizes

```vue
<SButton size="large" type="primary">Large</SButton>
<SButton size="middle" type="primary">Middle</SButton>
<SButton size="small" type="primary">Small</SButton>
<SButton size="mini" type="primary">Mini</SButton>
```

## Disabled

```vue
<SButton disabled type="primary">Disabled</SButton>
```

## Text Button

```vue
<SButton type="text">Text Button</SButton>
```

## Props

| Name | Description | Type | Default |
|------|-------------|------|---------|
| type | Button type | `'primary' \| 'success' \| 'danger' \| 'warning' \| 'info' \| 'default' \| 'text'` | `'default'` |
| size | Button size | `'large' \| 'middle' \| 'small' \| 'mini'` | `'middle'` |
| disabled | Disabled state | `boolean` | `false` |
| nativeType | Native button type | `'button' \| 'submit' \| 'reset'` | `'button'` |

## React Props Difference

| Name | Description | Type | Default |
|------|-------------|------|---------|
| onClick | Click handler | `(e: MouseEvent) => void` | - |