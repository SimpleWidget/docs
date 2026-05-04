# Radio

Radio button component.

## Basic Usage

::: tabs vue3 vue2 react
@tab vue3

```vue
<SRadio v-model="value" label="1">Option 1</SRadio>
<SRadio v-model="value" label="2">Option 2</SRadio>
```

@tab vue2

```vue
<SRadio v-model="value" label="1">Option 1</SRadio>
<SRadio v-model="value" label="2">Option 2</SRadio>
```

@tab react

```tsx
<SRadio value="1" checked={value === '1'} onChange={() => setValue('1')}>Option 1</SRadio>
<SRadio value="2" checked={value === '2'} onChange={() => setValue('2')}>Option 2</SRadio>
```
:::

## Group

::: tabs vue3 vue2 react
@tab vue3

```vue
<SRadioGroup v-model="value">
  <SRadio label="Option A" value="a" />
  <SRadio label="Option B" value="b" />
  <SRadio label="Option C" value="c" />
</SRadioGroup>
```

@tab vue2

```vue
<SRadioGroup v-model="value">
  <SRadio label="Option A" value="a" />
  <SRadio label="Option B" value="b" />
  <SRadio label="Option C" value="c" />
</SRadioGroup>
```

@tab react

```tsx
<SRadioGroup value={value} onChange={setValue}>
  <SRadio label="Option A" value="a" />
  <SRadio label="Option B" value="b" />
  <SRadio label="Option C" value="c" />
</SRadioGroup>
```
:::

## Props

### Vue3 / Vue2 / React

| Name | Description | Type | Default |
|------|-------------|------|---------|
| modelValue / v-model / value | Selected value | `string \| number` | - |
| label | Radio label | `string \| number` | - |
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