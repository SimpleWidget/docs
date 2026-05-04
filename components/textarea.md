# Textarea

Multi-line text input.

## Basic Usage

::: details Vue3

```vue
<STextarea v-model="value" placeholder="Please input" />
```

:::

::: details Vue2

```vue
<STextarea v-model="value" placeholder="Please input" />
```

:::

::: details React

```tsx
<STextarea value={value} onChange={setValue} placeholder="Please input" />
```

:::

## Props

| Name | Description | Type | Default |
|------|-------------|------|---------|
| modelValue / v-model / value | Text value | `string` | `''` |
| placeholder | Placeholder text | `string` | - |
| disabled | Disabled state | `boolean` | `false` |
| rows | Number of rows | `number` | `4` |
| maxlength | Maximum length | `number` | - |

## Events

| Name | Description | Vue3 | Vue2 | React |
|------|-------------|------|------|-------|
| change | Value change | `@change` | `@change` | `onChange` |