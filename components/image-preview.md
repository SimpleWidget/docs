# ImagePreview

Image preview component.

## Basic Usage

```vue
<SImagePreview :src="imageSrc" v-model="visible" />
```

## Props

| Name | Description | Type | Default |
|------|-------------|------|---------|
| modelValue / v-model | Visibility state | `boolean` | `false` |
| src | Image URL | `string` | - |
| zIndex | Z-index | `number` | `2000` |

## Events

| Name | Description |
|------|-------------|
| update:modelValue | Visibility change |
| close | Triggered when closed |

## React Props Difference

| Name | Description | Type | Default |
|------|-------------|------|---------|
| visible | Visibility state | `boolean` | `false` |
| onClose | Close handler | `() => void` | - |