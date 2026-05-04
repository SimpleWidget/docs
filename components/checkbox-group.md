# Checkbox Group

Group of checkboxes.

## Basic Usage

::: details Vue3

```vue
<SCheckboxGroup v-model="values" :options="['A', 'B', 'C']" />
```

:::

::: details Vue2

```vue
<SCheckboxGroup v-model="values" :options="['A', 'B', 'C']" />
```

:::

::: details React

```tsx
<SCheckboxGroup value={values} onChange={setValues} options={['A', 'B', 'C']} />
```

:::

## Props

| Name | Description | Type | Default |
|------|-------------|------|---------|
| modelValue / v-model / value | Selected values | `string[]` | `[]` |
| options | Options array | `string[] \| object[]` | `[]` |
| disabled | Disabled state | `boolean` | `false` |

## Events

| Name | Description | Vue3 | Vue2 | React |
|------|-------------|------|------|-------|
| change | Selection change | `@change` | `@change` | `onChange` |