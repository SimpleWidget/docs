# Input

Text input component.

## Basic Usage

```vue
<SInput v-model="value" placeholder="Please input" />
```

## Props

| Name | Description | Type | Default |
|------|-------------|------|---------|
| modelValue | Input value | `string` | `''` |
| type | Input type | `'text' \| 'password' \| 'number' \| 'email'` | `'text'` |
| placeholder | Placeholder text | `string` | - |
| disabled | Disabled state | `boolean` | `false` |
| clearable | Show clear button | `boolean` | `false` |
| size | Input size | `'large' \| 'middle' \| 'small'` | `'middle'` |
| prefix | Prefix icon | `string` | - |
| suffix | Suffix icon | `string` | - |

## Events

| Name | Description |
|------|-------------|
| input | Triggered on input |
| change | Triggered on change |
| focus | Triggered on focus |
| blur | Triggered on blur |
| clear | Triggered when cleared |