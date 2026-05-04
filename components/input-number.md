# InputNumber

Number input component.

## Basic Usage

::: tabs vue3 vue2 react
@tab vue3

```vue
<SInputNumber v-model="num" :min="0" :max="100" />
```

@tab vue2

```vue
<SInputNumber v-model="num" :min="0" :max="100" />
```

@tab react

```tsx
<SInputNumber value={num} onChange={setNum} min={0} max={100} />
```
:::

## Step

::: tabs vue3 vue2 react
@tab vue3

```vue
<SInputNumber v-model="num" :step="10" />
```

@tab vue2

```vue
<SInputNumber v-model="num" :step="10" />
```

@tab react

```tsx
<SInputNumber value={num} onChange={setNum} step={10} />
```
:::

## Props

### Vue3 / Vue2 / React

| Name | Description | Type | Default |
|------|-------------|------|---------|
| modelValue / v-model / value | Current value | `number` | `0` |
| min | Minimum value | `number` | `-Infinity` |
| max | Maximum value | `number` | `Infinity` |
| step | Step value | `number` | `1` |
| precision | Decimal precision | `number` | - |
| disabled | Disabled state | `boolean` | `false` |
| size | Input size | `'large' \| 'middle' \| 'small'` | `'middle'` |

## Events

### Vue3 / Vue2

| Name | Description |
|------|-------------|
| change | Triggered when value changes |

### React

| Name | Description |
|------|-------------|
| onChange | Triggered when value changes |