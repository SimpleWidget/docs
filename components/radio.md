# Radio

Radio button component.

## Basic Usage

::: details Vue3

```vue
<SRadioGroup v-model="value">
  <SRadio label="Option A" value="a" />
  <SRadio label="Option B" value="b" />
</SRadioGroup>
```

:::

::: details Vue2

```vue
<SRadioGroup v-model="value">
  <SRadio label="Option A" value="a" />
  <SRadio label="Option B" value="b" />
</SRadioGroup>
```

:::

::: details React

```tsx
<SRadioGroup value={value} onChange={setValue}>
  <SRadio label="Option A" value="a" />
  <SRadio label="Option B" value="b" />
</SRadioGroup>
```

:::

## Props

| Name | Description | Type | Default |
|------|-------------|------|---------|
| modelValue / v-model / value | Selected value | `string \| number` | - |
| label | Radio label | `string \| number` | - |
| disabled | Disabled state | `boolean` | `false` |

## Events

| Name | Description | Vue3 | Vue2 | React |
|------|-------------|------|------|-------|
| change | Selection change | `@change` | `@change` | `onChange` |