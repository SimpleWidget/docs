# Textarea

Multi-line text input.

## Basic Usage

::: tabs vue3 vue2 react
@tab vue3

```vue
<STextarea v-model="value" placeholder="Please input" />
```

@tab vue2

```vue
<STextarea v-model="value" placeholder="Please input" />
```

@tab react

```tsx
<STextarea value={value} onChange={setValue} placeholder="Please input" />
```
:::

## Rows

::: tabs vue3 vue2 react
@tab vue3

```vue
<STextarea v-model="value" :rows="6" />
```

@tab vue2

```vue
<STextarea v-model="value" :rows="6" />
```

@tab react

```tsx
<STextarea value={value} onChange={setValue} rows={6} />
```
:::

## Props

### Vue3 / Vue2 / React

| Name | Description | Type | Default |
|------|-------------|------|---------|
| modelValue / v-model / value | Text value | `string` | `''` |
| placeholder | Placeholder text | `string` | - |
| disabled | Disabled state | `boolean` | `false` |
| rows | Number of rows | `number` | `4` |
| maxlength | Maximum length | `number` | - |
| showCount | Show character count | `boolean` | `false` |
| autosize | Auto height | `boolean` | `false` |

## Events

### Vue3 / Vue2

| Name | Description |
|------|-------------|
| change | Triggered when value changes |
| focus | Triggered on focus |
| blur | Triggered on blur |

### React

| Name | Description |
|------|-------------|
| onChange | Triggered when value changes |
| onFocus | Triggered on focus |
| onBlur | Triggered on blur |