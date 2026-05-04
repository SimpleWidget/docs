# Dialog

Modal dialog component.

## Basic Usage

```vue
<SDialog v-model="visible" title="Dialog Title">
  <div>Dialog content</div>
  <template #footer>
    <SButton @click="visible = false">Cancel</SButton>
    <SButton type="primary" @click="handleConfirm">Confirm</SButton>
  </template>
</SDialog>
```

## Props

| Name | Description | Type | Default |
|------|-------------|------|---------|
| modelValue / v-model | Visibility state | `boolean` | `false` |
| title | Dialog title | `string` | - |
| width | Dialog width | `string` | `'500px'` |
| maskClose | Click mask to close | `boolean` | `true` |

## Events

| Name | Description |
|------|-------------|
| confirm | Triggered when confirmed |
| cancel | Triggered when cancelled |
| update:modelValue | Visibility change |

## React Props Difference

| Name | Description | Type | Default |
|------|-------------|------|---------|
| visible | Visibility state | `boolean` | `false` |
| onClose | Close handler | `() => void` | - |
| onConfirm | Confirm handler | `() => void` | - |
| onCancel | Cancel handler | `() => void` | - |