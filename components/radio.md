# Radio

Radio button component.

## Basic Usage

```vue
<SRadio v-model="value" label="1">Option 1</SRadio>
<SRadio v-model="value" label="2">Option 2</SRadio>
```

## Props

| Name | Description | Type | Default |
|------|-------------|------|---------|
| modelValue | Selected value | `string \| number` | - |
| label | Radio label | `string \| number` | - |
| disabled | Disabled state | `boolean` | `false` |

## Events

| Name | Description |
|------|-------------|
| change | Triggered when selection changes |