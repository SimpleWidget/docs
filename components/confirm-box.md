# ConfirmBox

Confirmation dialog.

## Basic Usage

```vue
<SConfirmBox
  title="Confirm"
  message="Are you sure?"
  @confirm="handleConfirm"
  @cancel="handleCancel"
/>
```

## Types

```vue
<SConfirmBox type="warning" message="Warning message" />
<SConfirmBox type="danger" message="Danger action" />
<SConfirmBox type="info" message="Info message" />
```

## Props

| Name | Description | Type | Default |
|------|-------------|------|---------|
| title | Dialog title | `string` | `'Confirm'` |
| message | Dialog message | `string` | - |
| confirmText | Confirm button text | `string` | `'Confirm'` |
| cancelText | Cancel button text | `string` | `'Cancel'` |
| type | Dialog type | `'warning' \| 'danger' \| 'info'` | `'warning'` |

## Events

| Name | Description |
|------|-------------|
| confirm | Triggered when confirmed |
| cancel | Triggered when cancelled |

## React Props Difference

| Name | Description | Type | Default |
|------|-------------|------|---------|
| onConfirm | Confirm handler | `() => void` | - |
| onCancel | Cancel handler | `() => void` | - |