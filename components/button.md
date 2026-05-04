# Button

Buttons are used to trigger actions.

## Basic Usage

::: details Vue3

```vue
<SButton type="primary">Primary</SButton>
<SButton type="success">Success</SButton>
<SButton type="danger">Danger</SButton>
```

:::

::: details Vue2

```vue
<SButton type="primary">Primary</SButton>
<SButton type="success">Success</SButton>
<SButton type="danger">Danger</SButton>
```

:::

::: details React

```tsx
<SButton type="primary">Primary</SButton>
<SButton type="success">Success</SButton>
<SButton type="danger">Danger</SButton>
```

:::

## Sizes

::: details Vue3

```vue
<SButton size="large">Large</SButton>
<SButton size="middle">Middle</SButton>
<SButton size="small">Small</SButton>
```

:::

::: details Vue2

```vue
<SButton size="large">Large</SButton>
<SButton size="middle">Middle</SButton>
<SButton size="small">Small</SButton>
```

:::

::: details React

```tsx
<SButton size="large">Large</SButton>
<SButton size="middle">Middle</SButton>
<SButton size="small">Small</SButton>
```

:::

## Disabled

::: details Vue3

```vue
<SButton disabled>Disabled</SButton>
```

:::

::: details Vue2

```vue
<SButton disabled>Disabled</SButton>
```

:::

::: details React

```tsx
<SButton disabled>Disabled</SButton>
```

:::

## Props

| Name | Description | Type | Default |
|------|-------------|------|---------|
| type | Button type | `'primary' \| 'success' \| 'danger' \| 'warning' \| 'info' \| 'default'` | `'default'` |
| size | Button size | `'large' \| 'middle' \| 'small' \| 'mini'` | `'middle'` |
| disabled | Disabled state | `boolean` | `false` |
| nativeType | Native button type | `'button' \| 'submit' \| 'reset'` | `'button'` |

## Events

| Name | Description | Vue3 | Vue2 | React |
|------|-------------|------|------|-------|
| click | Click event | `@click` | `@click` | `onClick` prop |