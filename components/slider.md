# Slider

Slider input component.

## Basic Usage

::: tabs vue3 vue2 react
@tab vue3

```vue
<SSlider v-model="value" :min="0" :max="100" />
```

@tab vue2

```vue
<SSlider v-model="value" :min="0" :max="100" />
```

@tab react

```tsx
<SSlider value={value} onChange={setValue} min={0} max={100} />
```
:::

## With Range

::: tabs vue3 vue2 react
@tab vue3

```vue
<SSlider v-model="rangeValue" :min="0" :max="100" range />
```

@tab vue2

```vue
<SSlider v-model="rangeValue" :min="0" :max="100" range />
```

@tab react

```tsx
<SSlider value={rangeValue} onChange={setRangeValue} min={0} max={100} range />
```
:::

## With Input

::: tabs vue3 vue2 react
@tab vue3

```vue
<SSlider v-model="value" :min="0" :max="100" showInput />
```

@tab vue2

```vue
<SSlider v-model="value" :min="0" :max="100" showInput />
```

@tab react

```tsx
<SSlider value={value} onChange={setValue} min={0} max={100} showInput />
```
:::

## Props

### Vue3 / Vue2 / React

| Name | Description | Type | Default |
|------|-------------|------|---------|
| modelValue / v-model / value | Current value | `number` | `0` |
| min | Minimum value | `number` | `0` |
| max | Maximum value | `number` | `100` |
| step | Step value | `number` | `1` |
| disabled | Disabled state | `boolean` | `false` |
| showInput | Show input box | `boolean` | `false` |
| range | Enable range selection | `boolean` | `false` |

## Events

### Vue3 / Vue2

| Name | Description |
|------|-------------|
| change | Triggered when value changes |

### React

| Name | Description |
|------|-------------|
| onChange | Triggered when value changes |