# Button

Buttons are used to trigger actions.

## Basic Usage

Use `type` to set the button type.

::: tabs vue3 vue2 react
@tab vue3

```vue
<SButton type="primary">Primary</SButton>
<SButton type="success">Success</SButton>
<SButton type="danger">Danger</SButton>
<SButton type="warning">Warning</SButton>
<SButton type="info">Info</SButton>
<SButton type="default">Default</SButton>
```

@tab vue2

```vue
<SButton type="primary">Primary</SButton>
<SButton type="success">Success</SButton>
<SButton type="danger">Danger</SButton>
<SButton type="warning">Warning</SButton>
<SButton type="info">Info</SButton>
<SButton type="default">Default</SButton>
```

@tab react

```tsx
<SButton type="primary">Primary</SButton>
<SButton type="success">Success</SButton>
<SButton type="danger">Danger</SButton>
<SButton type="warning">Warning</SButton>
<SButton type="info">Info</SButton>
<SButton type="default">Default</SButton>
```
:::

## Sizes

::: tabs vue3 vue2 react
@tab vue3

```vue
<SButton size="large" type="primary">Large</SButton>
<SButton size="middle" type="primary">Middle</SButton>
<SButton size="small" type="primary">Small</SButton>
<SButton size="mini" type="primary">Mini</SButton>
```

@tab vue2

```vue
<SButton size="large" type="primary">Large</SButton>
<SButton size="middle" type="primary">Middle</SButton>
<SButton size="small" type="primary">Small</SButton>
<SButton size="mini" type="primary">Mini</SButton>
```

@tab react

```tsx
<SButton size="large" type="primary">Large</SButton>
<SButton size="middle" type="primary">Middle</SButton>
<SButton size="small" type="primary">Small</SButton>
<SButton size="mini" type="primary">Mini</SButton>
```
:::

## Disabled

::: tabs vue3 vue2 react
@tab vue3

```vue
<SButton disabled type="primary">Disabled</SButton>
```

@tab vue2

```vue
<SButton disabled type="primary">Disabled</SButton>
```

@tab react

```tsx
<SButton disabled type="primary">Disabled</SButton>
```
:::

## Text Button

::: tabs vue3 vue2 react
@tab vue3

```vue
<SButton type="text">Text Button</SButton>
```

@tab vue2

```vue
<SButton type="text">Text Button</SButton>
```

@tab react

```tsx
<SButton type="text">Text Button</SButton>
```
:::

## Props

### Vue3 / Vue2

| Name | Description | Type | Default |
|------|-------------|------|---------|
| type | Button type | `'primary' \| 'success' \| 'danger' \| 'warning' \| 'info' \| 'default' \| 'text'` | `'default'` |
| size | Button size | `'large' \| 'middle' \| 'small' \| 'mini'` | `'middle'` |
| disabled | Disabled state | `boolean` | `false` |
| nativeType | Native button type | `'button' \| 'submit' \| 'reset'` | `'button'` |

### React

| Name | Description | Type | Default |
|------|-------------|------|---------|
| type | Button type | `'primary' \| 'success' \| 'warning' \| 'danger' \| 'info' \| 'text' \| 'default'` | `'default'` |
| size | Button size | `'medium' \| 'large' \| 'small' \| 'mini' \| 'middle'` | `'middle'` |
| disabled | Disabled state | `boolean` | `false'` |
| nativeType | Native button type | `'button' \| 'submit' \| 'reset'` | `'button'` |
| onClick | Click handler | `(e: MouseEvent) => void` | - |