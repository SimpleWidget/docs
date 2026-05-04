# Switch

Toggle switch component.

## Basic Usage

```vue
<SSwitch v-model="checked" />
```

## With Text

```vue
<SSwitch v-model="checked" activeText="ON" inactiveText="OFF" />
```

## Sizes

```vue
<SSwitch v-model="checked" size="large" />
<SSwitch v-model="checked" size="middle" />
<SSwitch v-model="checked" size="small" />
```

## Props

| Name | Description | Type | Default |
|------|-------------|------|---------|
| modelValue / v-model | Switch state | `boolean` | `false` |
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

## React Props Difference

| Name | Description | Type | Default |
|------|-------------|------|---------|
| checked | Switch state | `boolean` | `false` |
| onChange | Change handler | `(checked: boolean) => void` | - |