# Radio Group

Group of radio buttons.

## Basic Usage

::: tabs vue3 vue2 react
@tab vue3

```vue
<SRadioGroup v-model="value" :options="['A', 'B', 'C']" />
```

@tab vue2

```vue
<SRadioGroup v-model="value" :options="['A', 'B', 'C']" />
```

@tab react

```tsx
<SRadioGroup value={value} onChange={setValue} options={['A', 'B', 'C']} />
```
:::

## With Options

::: tabs vue3 vue2 react
@tab vue3

```vue
<SRadioGroup v-model="value" :options="options" />
```

@tab vue2

```vue
<SRadioGroup v-model="value" :options="options" />
```

@tab react

```tsx
<SRadioGroup value={value} onChange={setValue} options={options} />
```
:::

## Props

### Vue3 / Vue2 / React

| Name | Description | Type | Default |
|------|-------------|------|---------|
| modelValue / v-model / value | Selected value | `string \| number` | - |
| options | Options array | `string[] \| number[]` | `[]` |
| disabled | Disabled state | `boolean` | `false` |
| size | Group size | `'large' \| 'middle' \| 'small'` | `'middle'` |

## Events

### Vue3 / Vue2

| Name | Description |
|------|-------------|
| change | Triggered when selection changes |

### React

| Name | Description |
|------|-------------|
| onChange | Triggered when selection changes |