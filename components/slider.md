# Slider

Slider input component.

## Basic Usage

```vue
<SSlider v-model="value" :min="0" :max="100" />
```

## Props

| Name | Description | Type | Default |
|------|-------------|------|---------|
| modelValue | Current value | `number` | `0` |
| min | Minimum value | `number` | `0` |
| max | Maximum value | `number` | `100` |
| step | Step value | `number` | `1` |
| disabled | Disabled state | `boolean` | `false` |
| showInput | Show input box | `boolean` | `false` |
| range | Enable range selection | `boolean` | `false` |

## Events

| Name | Description |
|------|-------------|
| change | Triggered when value changes |