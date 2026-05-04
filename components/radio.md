# Radio

Radio button component.

## Basic Usage

```vue
<SRadio v-model="value" label="1">Option 1</SRadio>
<SRadio v-model="value" label="2">Option 2</SRadio>
```

## Group

```vue
<SRadioGroup v-model="value">
  <SRadio label="Option A" value="a" />
  <SRadio label="Option B" value="b" />
  <SRadio label="Option C" value="c" />
</SRadioGroup>
```

## Props

| Name | Description | Type | Default |
|------|-------------|------|---------|
| modelValue / v-model | Selected value | `string \| number` | - |
| label | Radio label | `string \| number` | - |
| disabled | Disabled state | `boolean` | `false` |

## Events

| Name | Description |
|------|-------------|
| change | Triggered when selection changes |

## React Props Difference

| Name | Description | Type | Default |
|------|-------------|------|---------|
| checked | Selected state | `boolean` | `false` |
| onChange | Change handler | `(value: string \| number) => void` | - |