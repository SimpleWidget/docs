# ImagePreview

Image preview component.

## Basic Usage

::: details Vue3

```vue
<SImagePreview :src="imageSrc" v-model="visible" />
```

:::

::: details Vue2

```vue
<SImagePreview :src="imageSrc" v-model="visible" />
```

:::

::: details React

```tsx
<SImagePreview src={imageSrc} visible={visible} onClose={setVisible} />
```

:::

## Props

| Name | Description | Type | Default |
|------|-------------|------|---------|
| modelValue / v-model / visible | Visibility state | `boolean` | `false` |
| src | Image URL | `string` | - |

## Events

| Name | Description | Vue3 | Vue2 | React |
|------|-------------|------|------|-------|
| close | Close event | `@close` | `@close` | `onClose` |