# Slider

Slider input component.

## Basic Usage

::: details Vue3

```vue
<SSlider v-model="value" :min="0" :max="100" />
```

:::

::: details Vue2

```vue
<SSlider v-model="value" :min="0" :max="100" />
```

:::

::: details React

```tsx
<SSlider value={value} onChange={setValue} min={0} max={100} />
```

:::

## Props

| Name | Description | Type | Default |
|------|-------------|------|---------|
| modelValue / v-model / value | Current value | `number` | `0` |
| min | Minimum value | `number` | `0` |
| max | Maximum value | `number` | `100` |
| step | Step value | `number` | `1` |
| disabled | Disabled state | `boolean` | `false` |
| range | Enable range | `boolean` | `false` |

## Events

| Name | Description | Vue3 | Vue2 | React |
|------|-------------|------|------|-------|
| change | Value change | `@change` | `@change` | `onChange` |