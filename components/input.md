# Input

Text input component.

## Basic Usage

```vue
<SInput v-model="value" placeholder="Please input" />
```

## Disabled

```vue
<SInput disabled placeholder="Disabled" />
```

## Sizes

```vue
<SInput size="large" placeholder="Large size" />
<SInput size="middle" placeholder="Middle size" />
<SInput size="small" placeholder="Small size" />
```

## Password

```vue
<SInput type="password" placeholder="Password" showPassword />
```

## Props

| Name | Description | Type | Default |
|------|-------------|------|---------|
| modelValue / v-model | Input value | `string` | `''` |
| type | Input type | `'text' \| 'password' \| 'number'` | `'text'` |
| placeholder | Placeholder text | `string` | - |
| disabled | Disabled state | `boolean` | `false` |
| clearable | Show clear button | `boolean` | `false` |
| size | Input size | `'large' \| 'middle' \| 'small'` | `'middle'` |

## Events

| Name | Description |
|------|-------------|
| update:modelValue | Triggered on input |
| change | Triggered on change |
| focus | Triggered on focus |
| blur | Triggered on blur |
| clear | Triggered when cleared |

## React Props Difference

| Name | Description | Type | Default |
|------|-------------|------|---------|
| value | Input value | `string` | `''` |
| onChange | Change handler | `(value: string) => void` | - |