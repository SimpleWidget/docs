# Switch

Toggle switch component.

## Basic Usage

::: details Vue3

```vue
<SSwitch v-model="checked" />
```

:::

::: details Vue2

```vue
<SSwitch v-model="checked" />
```

:::

::: details React

```tsx
<SSwitch checked={checked} onChange={setChecked} />
```

:::

## With Text

::: details Vue3

```vue
<SSwitch v-model="checked" activeText="ON" inactiveText="OFF" />
```

:::

::: details Vue2

```vue
<SSwitch v-model="checked" activeText="ON" inactiveText="OFF" />
```

:::

::: details React

```tsx
<SSwitch checked={checked} onChange={setChecked} activeText="ON" inactiveText="OFF" />
```

:::

## Props

| Name | Description | Type | Default |
|------|-------------|------|---------|
| modelValue / v-model / checked | Switch state | `boolean` | `false` |
| disabled | Disabled state | `boolean` | `false` |
| size | Switch size | `'large' \| 'middle' \| 'small'` | `'middle'` |
| activeText | Active text | `string` | - |
| inactiveText | Inactive text | `string` | - |

## Events

| Name | Description | Vue3 | Vue2 | React |
|------|-------------|------|------|-------|
| change | Switch change | `@change` | `@change` | `onChange` |