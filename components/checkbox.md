# Checkbox

Select one or more options.

## Basic Usage

::: details Vue3

```vue
<SCheckbox v-model="checked">Option</SCheckbox>
```

:::

::: details Vue2

```vue
<SCheckbox v-model="checked">Option</SCheckbox>
```

:::

::: details React

```tsx
<SCheckbox checked={checked} onChange={setChecked}>Option</SCheckbox>
```

:::

## Group

::: details Vue3

```vue
<SCheckboxGroup v-model="checkedList">
  <SCheckbox label="Option A" value="a" />
  <SCheckbox label="Option B" value="b" />
</SCheckboxGroup>
```

:::

::: details Vue2

```vue
<SCheckboxGroup v-model="checkedList">
  <SCheckbox label="Option A" value="a" />
  <SCheckbox label="Option B" value="b" />
</SCheckboxGroup>
```

:::

::: details React

```tsx
<SCheckboxGroup value={checkedList} onChange={setCheckedList}>
  <SCheckbox label="Option A" value="a" />
  <SCheckbox label="Option B" value="b" />
</SCheckboxGroup>
```

:::

## Props

| Name | Description | Type | Default |
|------|-------------|------|---------|
| modelValue / v-model / checked | Checked state | `boolean` | `false` |
| label | Checkbox label | `string` | - |
| disabled | Disabled state | `boolean` | `false` |
| value | Checkbox value (in group) | `string \| number` | - |

## Events

| Name | Description | Vue3 | Vue2 | React |
|------|-------------|------|------|-------|
| change | Checked change | `@change` | `@change` | `onChange` |