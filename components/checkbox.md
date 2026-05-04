# Checkbox

Select one or more options.

## Basic Usage

::: tabs vue3 vue2 react
@tab vue3

```vue
<SCheckbox v-model="checked">Option</SCheckbox>
```

@tab vue2

```vue
<SCheckbox v-model="checked">Option</SCheckbox>
```

@tab react

```tsx
<SCheckbox checked={checked} onChange={setChecked}>Option</SCheckbox>
```
:::

## Disabled

::: tabs vue3 vue2 react
@tab vue3

```vue
<SCheckbox disabled v-model="checked">Disabled</SCheckbox>
```

@tab vue2

```vue
<SCheckbox disabled v-model="checked">Disabled</SCheckbox>
```

@tab react

```tsx
<SCheckbox disabled checked={checked} onChange={setChecked}>Disabled</SCheckbox>
```
:::

## Group

::: tabs vue3 vue2 react
@tab vue3

```vue
<SCheckboxGroup v-model="checkedList">
  <SCheckbox label="Option A" value="a" />
  <SCheckbox label="Option B" value="b" />
  <SCheckbox label="Option C" value="c" />
</SCheckboxGroup>
```

@tab vue2

```vue
<SCheckboxGroup v-model="checkedList">
  <SCheckbox label="Option A" value="a" />
  <SCheckbox label="Option B" value="b" />
  <SCheckbox label="Option C" value="c" />
</SCheckboxGroup>
```

@tab react

```tsx
<SCheckboxGroup value={checkedList} onChange={setCheckedList}>
  <SCheckbox label="Option A" value="a" />
  <SCheckbox label="Option B" value="b" />
  <SCheckbox label="Option C" value="c" />
</SCheckboxGroup>
```
:::

## Props

### Vue3 / Vue2 / React

| Name | Description | Type | Default |
|------|-------------|------|---------|
| modelValue / v-model / checked | Checked state | `boolean` | `false` |
| label | Checkbox label | `string` | - |
| disabled | Disabled state | `boolean` | `false` |
| indeterminate | Indeterminate state | `boolean` | `false` |
| value | Checkbox value (in group) | `string \| number` | - |

## Events

### Vue3 / Vue2

| Name | Description |
|------|-------------|
| change | Triggered when checked state changes |

### React

| Name | Description |
|------|-------------|
| onChange | Triggered when checked state changes |