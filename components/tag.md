# Tag

Tags are used to categorize or mark items.

## Basic Usage

::: tabs vue3 vue2 react
@tab vue3

```vue
<STag type="primary">Primary</STag>
<STag type="success">Success</STag>
<STag type="danger">Danger</STag>
<STag type="warning">Warning</STag>
<STag type="info">Info</STag>
<STag type="default">Default</STag>
```

@tab vue2

```vue
<STag type="primary">Primary</STag>
<STag type="success">Success</STag>
<STag type="danger">Danger</STag>
<STag type="warning">Warning</STag>
<STag type="info">Info</STag>
<STag type="default">Default</STag>
```

@tab react

```tsx
<STag type="primary">Primary</STag>
<STag type="success">Success</STag>
<STag type="danger">Danger</STag>
<STag type="warning">Warning</STag>
<STag type="info">Info</STag>
<STag type="default">Default</STag>
```
:::

## Sizes

::: tabs vue3 vue2 react
@tab vue3

```vue
<STag size="large" type="primary">Large</STag>
<STag size="middle" type="primary">Middle</STag>
<STag size="small" type="primary">Small</STag>
<STag size="mini" type="primary">Mini</STag>
```

@tab vue2

```vue
<STag size="large" type="primary">Large</STag>
<STag size="middle" type="primary">Middle</STag>
<STag size="small" type="primary">Small</STag>
<STag size="mini" type="primary">Mini</STag>
```

@tab react

```tsx
<STag size="large" type="primary">Large</STag>
<STag size="middle" type="primary">Middle</STag>
<STag size="small" type="primary">Small</STag>
<STag size="mini" type="primary">Mini</STag>
```
:::

## Closeable

::: tabs vue3 vue2 react
@tab vue3

```vue
<STag closable type="primary" @close="onClose">Primary</STag>
```

@tab vue2

```vue
<STag closable type="primary" @close="onClose">Primary</STag>
```

@tab react

```tsx
<STag closable type="primary" onClose={onClose}>Primary</STag>
```
:::

## Round

::: tabs vue3 vue2 react
@tab vue3

```vue
<STag round type="primary">Round Tag</STag>
```

@tab vue2

```vue
<STag round type="primary">Round Tag</STag>
```

@tab react

```tsx
<STag round type="primary">Round Tag</STag>
```
:::

## Simple Mode

::: tabs vue3 vue2 react
@tab vue3

```vue
<STag simple type="primary">Simple Primary</STag>
```

@tab vue2

```vue
<STag simple type="primary">Simple Primary</STag>
```

@tab react

```tsx
<STag simple type="primary">Simple Primary</STag>
```
:::

## Props

### Vue3 / Vue2 / React

| Name | Description | Type | Default |
|------|-------------|------|---------|
| type | Tag type | `'primary' \| 'success' \| 'danger' \| 'warning' \| 'info' \| 'default'` | `'primary'` |
| size | Tag size | `'large' \| 'middle' \| 'small' \| 'mini'` | `'middle'` |
| closable | Show close button | `boolean` | `false` |
| round | Round style | `boolean` | `false` |
| simple | Simple style | `boolean` | `false` |
| block | Block element | `boolean` | `false` |
| line | Line style | `boolean` | `false` |

## Events

### Vue3 / Vue2

| Name | Description |
|------|-------------|
| close | Triggered when close button is clicked |

### React

| Name | Description |
|------|-------------|
| onClose | Triggered when close button is clicked |