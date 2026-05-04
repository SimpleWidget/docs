# ImagePreview

Image preview component.

## Basic Usage

::: tabs vue3 vue2 react
@tab vue3

```vue
<SImagePreview :src="imageSrc" v-model="visible" />
```

@tab vue2

```vue
<SImagePreview :src="imageSrc" v-model="visible" />
```

@tab react

```tsx
<SImagePreview src={imageSrc} visible={visible} onClose={setVisible} />
```
:::

## Props

### Vue3 / Vue2 / React

| Name | Description | Type | Default |
|------|-------------|------|---------|
| modelValue / v-model / visible | Visibility state | `boolean` | `false` |
| src | Image URL | `string` | - |
| zIndex | Z-index | `number` | `2000` |

## Events

### Vue3 / Vue2

| Name | Description |
|------|-------------|
| update:modelValue | Visibility change |
| close | Triggered when closed |

### React

| Name | Description |
|------|-------------|
| onClose | Triggered when closed |