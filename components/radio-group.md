# Radio Group

Group of radio buttons.

## Basic Usage

::: details Vue3

```vue
<SRadioGroup v-model="value" :options="['A', 'B', 'C']" />
```

:::

::: details Vue2

```vue
<SRadioGroup v-model="value" :options="['A', 'B', 'C']" />
```

:::

::: details React

```tsx
<SRadioGroup value={value} onChange={setValue} options={['A', 'B', 'C']} />
```

:::

## Props

| Name | Description | Type | Default |
|------|-------------|------|---------|
| modelValue / v-model / value | Selected value | `string \| number` | - |
| options | Options array | `string[] \| number[]` | `[]` |
| disabled | Disabled state | `boolean` | `false` |
| size | Group size | `'large' \| 'middle' \| 'small'` | `'middle'` |

## Events

| Name | Description | Vue3 | Vue2 | React |
|------|-------------|------|------|-------|
| change | Selection change | `@change` | `@change` | `onChange` |