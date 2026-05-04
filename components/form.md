# Form

Form component with validation.

## Basic Usage

::: details Vue3

```vue
<SForm :model="formData" :rules="rules" ref="formRef">
  <SFormItem label="Name" prop="name">
    <SInput v-model="formData.name" />
  </SFormItem>
</SForm>
```

:::

::: details Vue2

```vue
<SForm :model="formData" :rules="rules" ref="formRef">
  <SFormItem label="Name" prop="name">
    <SInput v-model="formData.name" />
  </SFormItem>
</SForm>
```

:::

::: details React

```tsx
<SForm model={formData} rules={rules}>
  <SFormItem label="Name" prop="name">
    <SInput
      value={formData.name}
      onChange={(v) => setFormData({...formData, name: v})}
    />
  </SFormItem>
</SForm>
```

:::

## Props

| Name | Description | Type | Default |
|------|-------------|------|---------|
| model | Form data object | `object` | - |
| rules | Validation rules | `object` | - |
| labelWidth | Label width | `string` | - |
| labelPosition | Label position | `'left' \| 'right' \| 'top'` | `'right'` |

## FormItem Props

| Name | Description | Type | Default |
|------|-------------|------|---------|
| label | Label text | `string` | - |
| prop | Field name | `string` | - |
| required | Required field | `boolean` | `false` |

## Events

| Name | Description | Vue3 | Vue2 | React |
|------|-------------|------|------|-------|
| validate | Form validation | `@validate` | `@validate` | - |
| reset | Form reset | `@reset` | `@reset` | - |