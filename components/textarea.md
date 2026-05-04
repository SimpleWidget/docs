# Textarea

Multi-line text input.

## Basic Usage

```vue
<STextarea v-model="value" placeholder="Please input" />
```

## Props

| Name | Description | Type | Default |
|------|-------------|------|---------|
| modelValue | Text value | `string` | `''` |
| placeholder | Placeholder text | `string` | - |
| disabled | Disabled state | `boolean` | `false` |
| rows | Number of rows | `number` | `4` |
| maxlength | Maximum length | `number` | - |
| showCount | Show character count | `boolean` | `false` |
| autosize | Auto height | `boolean` | `false` |

## Events

| Name | Description |
|------|-------------|
| change | Triggered when value changes |
| focus | Triggered on focus |
| blur | Triggered on blur |