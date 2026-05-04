# Form

Form component with validation.

## Basic Usage

::: tabs vue3 vue2 react
@tab vue3

```vue
<SForm :model="formData" :rules="rules" ref="formRef">
  <SFormItem label="Name" prop="name">
    <SInput v-model="formData.name" />
  </SFormItem>
  <SFormItem label="Email" prop="email">
    <SInput v-model="formData.email" />
  </SFormItem>
</SForm>
```

@tab vue2

```vue
<SForm :model="formData" :rules="rules" ref="formRef">
  <SFormItem label="Name" prop="name">
    <SInput v-model="formData.name" />
  </SFormItem>
  <SFormItem label="Email" prop="email">
    <SInput v-model="formData.email" />
  </SFormItem>
</SForm>
```

@tab react

```tsx
<SForm model={formData} rules={rules} ref={formRef}>
  <SFormItem label="Name" prop="name">
    <SInput value={formData.name} onChange={(v) => setFormData({...formData, name: v})} />
  </SFormItem>
  <SFormItem label="Email" prop="email">
    <SInput value={formData.email} onChange={(v) => setFormData({...formData, email: v})} />
  </SFormItem>
</SForm>
```
:::

## Form Props

### Vue3 / Vue2 / React

| Name | Description | Type | Default |
|------|-------------|------|---------|
| model | Form data object | `object` | - |
| rules | Validation rules | `object` | - |
| labelWidth | Label width | `string` | - |
| labelPosition | Label position | `'left' \| 'right' \| 'top'` | `'right'` |

### FormItem Props

| Name | Description | Type | Default |
|------|-------------|------|---------|
| label | Label text | `string` | - |
| prop | Field name | `string` | - |
| required | Required field | `boolean` | `false` |

## Events

### Vue3 / Vue2

| Name | Description |
|------|-------------|
| validate | Triggered when validating |
| reset | Triggered when reset |

## Methods

### Vue3 / Vue2 / React

| Name | Description |
|------|-------------|
| validate | Validate form |
| reset | Reset form |
| clearValidate | Clear validation |