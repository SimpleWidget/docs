# Dialog

Modal dialog component.

## Basic Usage

::: details Vue3

```vue
<SDialog v-model="visible" title="Dialog Title">
  <div>Dialog content</div>
  <template #footer>
    <SButton @click="visible = false">Cancel</SButton>
    <SButton type="primary" @click="handleConfirm">Confirm</SButton>
  </template>
</SDialog>
```

:::

::: details Vue2

```vue
<SDialog v-model="visible" title="Dialog Title">
  <div>Dialog content</div>
  <template slot="footer">
    <SButton @click="visible = false">Cancel</SButton>
    <SButton type="primary" @click="handleConfirm">Confirm</SButton>
  </template>
</SDialog>
```

:::

::: details React

```tsx
<SDialog visible={visible} onClose={() => setVisible(false)} title="Dialog Title">
  <div>Dialog content</div>
  <div className="dialog-footer">
    <SButton onClick={() => setVisible(false)}>Cancel</SButton>
    <SButton type="primary" onClick={handleConfirm}>Confirm</SButton>
  </div>
</SDialog>
```

:::

## Props

| Name | Description | Type | Default |
|------|-------------|------|---------|
| modelValue / v-model / visible | Visibility state | `boolean` | `false` |
| title | Dialog title | `string` | - |
| width | Dialog width | `string` | `'500px'` |
| maskClose | Click mask to close | `boolean` | `true` |

## Events

| Name | Description | Vue3 | Vue2 | React |
|------|-------------|------|------|-------|
| close | Close event | `@close` | `@close` | `onClose` |
| confirm | Confirm event | `@confirm` | `@confirm` | `onConfirm` |