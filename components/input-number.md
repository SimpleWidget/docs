# InputNumber

Number input component.

## Basic Usage

::: details Vue3

```vue
<SInputNumber v-model="num" :min="0" :max="100" />
```

:::

::: details Vue2

```vue
<SInputNumber v-model="num" :min="0" :max="100" />
```

:::

::: details React

```tsx
<SInputNumber value={num} onChange={setNum} min={0} max={100} />
```

:::

## Props

| Name | Description | Type | Default |
|------|-------------|------|---------|
| modelValue / v-model / value | Current value | `number` | `0` |
| min | Minimum value | `number` | `-Infinity` |
| max | Maximum value | `number` | `Infinity` |
| step | Step value | `number` | `1` |
| disabled | Disabled state | `boolean` | `false` |

## Events

| Name | Description | Vue3 | Vue2 | React |
|------|-------------|------|------|-------|
| change | Value change | `@change` | `@change` | `onChange` |