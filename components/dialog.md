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
| modelValue | Visibility state | `boolean` | `false` |
| title | Dialog title | `string` | - |
| width | Dialog width | `string` | `'500px'` |
| maskClose | Click mask to close | `boolean` | `true` |

## Events

| Name | Description |
|------|-------------|
| confirm | Triggered when confirmed |
| cancel | Triggered when cancelled |
| update:modelValue | Visibility change |