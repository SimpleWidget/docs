# Dialog

Modal dialog component.

## Basic Usage

::: tabs vue3 vue2 react
@tab vue3

```vue
<SDialog v-model="visible" title="Dialog Title">
  <div>Dialog content</div>
  <template #footer>
    <SButton @click="visible = false">Cancel</SButton>
    <SButton type="primary" @click="handleConfirm">Confirm</SButton>
  </template>
</SDialog>
```

@tab vue2

```vue
<SDialog v-model="visible" title="Dialog Title">
  <div>Dialog content</div>
  <template slot="footer">
    <SButton @click="visible = false">Cancel</SButton>
    <SButton type="primary" @click="handleConfirm">Confirm</SButton>
  </template>
</SDialog>
```

@tab react

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

### Vue3 / Vue2

| Name | Description | Type | Default |
|------|-------------|------|---------|
| modelValue / v-model | Visibility state | `boolean` | `false` |
| title | Dialog title | `string` | - |
| width | Dialog width | `string` | `'500px'` |
| maskClose | Click mask to close | `boolean` | `true` |

### React

| Name | Description | Type | Default |
|------|-------------|------|---------|
| visible | Visibility state | `boolean` | `false` |
| onClose | Close handler | `() => void` | - |
| title | Dialog title | `string` | - |
| width | Dialog width | `string` | `'500px'` |
| maskClose | Click mask to close | `boolean` | `true` |

## Events

### Vue3 / Vue2

| Name | Description |
|------|-------------|
| confirm | Triggered when confirmed |
| cancel | Triggered when cancelled |
| update:modelValue | Visibility change |

### React

| Name | Description |
|------|-------------|
| onConfirm | Triggered when confirmed |
| onCancel | Triggered when cancelled |
| onClose | Triggered when closed |