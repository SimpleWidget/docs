# Form

Form component with validation.

## Basic Usage

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

## Form Props

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

## Form Events

| Name | Description |
|------|-------------|
| validate | Triggered when validating |
| reset | Triggered when reset |

## Form Methods

| Name | Description |
|------|-------------|
| validate | Validate form |
| reset | Reset form |
| clearValidate | Clear validation |