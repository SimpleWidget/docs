# ConfirmBox

Confirmation dialog.

## Basic Usage

::: tabs vue3 vue2 react
@tab vue3

```vue
<SConfirmBox
  title="Confirm"
  message="Are you sure?"
  @confirm="handleConfirm"
  @cancel="handleCancel"
/>
```

@tab vue2

```vue
<SConfirmBox
  title="Confirm"
  message="Are you sure?"
  @confirm="handleConfirm"
  @cancel="handleCancel"
/>
```

@tab react

```tsx
<SConfirmBox
  title="Confirm"
  message="Are you sure?"
  onConfirm={handleConfirm}
  onCancel={handleCancel}
/>
```
:::

## Types

::: tabs vue3 vue2 react
@tab vue3

```vue
<SConfirmBox type="warning" message="Warning message" />
<SConfirmBox type="danger" message="Danger action" />
<SConfirmBox type="info" message="Info message" />
```

@tab vue2

```vue
<SConfirmBox type="warning" message="Warning message" />
<SConfirmBox type="danger" message="Danger action" />
<SConfirmBox type="info" message="Info message" />
```

@tab react

```tsx
<SConfirmBox type="warning" message="Warning message" />
<SConfirmBox type="danger" message="Danger action" />
<SConfirmBox type="info" message="Info message" />
```
:::

## Props

### Vue3 / Vue2 / React

| Name | Description | Type | Default |
|------|-------------|------|---------|
| title | Dialog title | `string` | `'Confirm'` |
| message | Dialog message | `string` | - |
| confirmText | Confirm button text | `string` | `'Confirm'` |
| cancelText | Cancel button text | `string` | `'Cancel'` |
| type | Dialog type | `'warning' \| 'danger' \| 'info'` | `'warning'` |

## Events

### Vue3 / Vue2

| Name | Description |
|------|-------------|
| confirm | Triggered when confirmed |
| cancel | Triggered when cancelled |

### React

| Name | Description |
|------|-------------|
| onConfirm | Triggered when confirmed |
| onCancel | Triggered when cancelled |