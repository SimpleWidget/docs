# Switch

Toggle switch component.

## Basic Usage

```vue
<SSwitch v-model="checked" />
```

## Props

| Name | Description | Type | Default |
|------|-------------|------|---------|
| modelValue | Switch state | `boolean` | `false` |
| disabled | Disabled state | `boolean` | `false` |
| size | Switch size | `'large' \| 'middle' \| 'small'` | `'middle'` |
| activeColor | Active color | `string` | - |
| inactiveColor | Inactive color | `string` | - |
| activeText | Active text | `string` | - |
| inactiveText | Inactive text | `string` | - |

## Events

| Name | Description |
|------|-------------|
| change | Triggered when switch state changes |