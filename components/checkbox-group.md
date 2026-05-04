# Checkbox Group

Group of checkboxes.

## Basic Usage

::: tabs vue3 vue2 react
@tab vue3

```vue
<SCheckboxGroup v-model="values" :options="['A', 'B', 'C']" />
```

@tab vue2

```vue
<SCheckboxGroup v-model="values" :options="['A', 'B', 'C']" />
```

@tab react

```tsx
<SCheckboxGroup value={values} onChange={setValues} options={['A', 'B', 'C']} />
```
:::

## With Labels

::: tabs vue3 vue2 react
@tab vue3

```vue
<SCheckboxGroup v-model="values" :options="options" />
```

@tab vue2

```vue
<SCheckboxGroup v-model="values" :options="options" />
```

@tab react

```tsx
<SCheckboxGroup value={values} onChange={setValues} options={options} />
```
:::

## Props

### Vue3 / Vue2 / React

| Name | Description | Type | Default |
|------|-------------|------|---------|
| modelValue / v-model / value | Selected values | `string[]` | `[]` |
| options | Options array | `string[] \| object[]` | `[]` |
| disabled | Disabled state | `boolean` | `false` |

## Events

### Vue3 / Vue2

| Name | Description |
|------|-------------|
| change | Triggered when selection changes |

### React

| Name | Description |
|------|-------------|
| onChange | Triggered when selection changes |