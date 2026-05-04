# ConfirmBox

Confirmation dialog.

## Basic Usage

::: details Vue3

```vue
<SConfirmBox
  title="Confirm"
  message="Are you sure?"
  @confirm="handleConfirm"
  @cancel="handleCancel"
/>
```

:::

::: details Vue2

```vue
<SConfirmBox
  title="Confirm"
  message="Are you sure?"
  @confirm="handleConfirm"
  @cancel="handleCancel"
/>
```

:::

::: details React

```tsx
<SConfirmBox
  title="Confirm"
  message="Are you sure?"
  onConfirm={handleConfirm}
  onCancel={handleCancel}
/>
```

:::

## Props

| Name | Description | Type | Default |
|------|-------------|------|---------|
| title | Dialog title | `string` | `'Confirm'` |
| message | Dialog message | `string` | - |
| type | Dialog type | `'warning' \| 'danger' \| 'info'` | `'warning'` |

## Events

| Name | Description | Vue3 | Vue2 | React |
|------|-------------|------|------|-------|
| confirm | Confirm event | `@confirm` | `@confirm` | `onConfirm` |
| cancel | Cancel event | `@cancel` | `@cancel` | `onCancel` |