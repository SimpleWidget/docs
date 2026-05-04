# Input

Text input component.

## Basic Usage

::: tabs vue3 vue2 react
@tab vue3

```vue
<SInput v-model="value" placeholder="Please input" />
```

@tab vue2

```vue
<SInput v-model="value" placeholder="Please input" />
```

@tab react

```tsx
<SInput value={value} onChange={setValue} placeholder="Please input" />
```
:::

## Disabled

::: tabs vue3 vue2 react
@tab vue3

```vue
<SInput disabled placeholder="Disabled" />
```

@tab vue2

```vue
<SInput disabled placeholder="Disabled" />
```

@tab react

```tsx
<SInput disabled placeholder="Disabled" />
```
:::

## Sizes

::: tabs vue3 vue2 react
@tab vue3

```vue
<SInput size="large" placeholder="Large size" />
<SInput size="middle" placeholder="Middle size" />
<SInput size="small" placeholder="Small size" />
```

@tab vue2

```vue
<SInput size="large" placeholder="Large size" />
<SInput size="middle" placeholder="Middle size" />
<SInput size="small" placeholder="Small size" />
```

@tab react

```tsx
<SInput size="large" placeholder="Large size" />
<SInput size="middle" placeholder="Middle size" />
<SInput size="small" placeholder="Small size" />
```
:::

## Password

::: tabs vue3 vue2 react
@tab vue3

```vue
<SInput type="password" placeholder="Password" showPassword />
```

@tab vue2

```vue
<SInput type="password" placeholder="Password" showPassword />
```

@tab react

```tsx
<SInput type="password" placeholder="Password" showPassword />
```
:::

## Props

### Vue3 / Vue2

| Name | Description | Type | Default |
|------|-------------|------|---------|
| modelValue / v-model | Input value | `string` | `''` |
| type | Input type | `'text' \| 'password' \| 'number'` | `'text'` |
| placeholder | Placeholder text | `string` | - |
| disabled | Disabled state | `boolean` | `false` |
| clearable | Show clear button | `boolean` | `false` |
| size | Input size | `'large' \| 'middle' \| 'small'` | `'middle'` |

### React

| Name | Description | Type | Default |
|------|-------------|------|---------|
| value | Input value | `string` | `''` |
| onChange | Change handler | `(value: string) => void` | - |
| type | Input type | `'text' \| 'password' \| 'number'` | `'text'` |
| placeholder | Placeholder text | `string` | - |
| disabled | Disabled state | `boolean` | `false` |
| clearable | Show clear button | `boolean` | `false` |
| size | Input size | `'large' \| 'middle' \| 'small'` | `'middle'` |

## Events

### Vue3 / Vue2

| Name | Description |
|------|-------------|
| update:modelValue | Triggered on input |
| change | Triggered on change |
| focus | Triggered on focus |
| blur | Triggered on blur |
| clear | Triggered when cleared |