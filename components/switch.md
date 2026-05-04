# Switch

Toggle switch component.

## Basic Usage

::: tabs vue3 vue2 react
@tab vue3

```vue
<SSwitch v-model="checked" />
```

@tab vue2

```vue
<SSwitch v-model="checked" />
```

@tab react

```tsx
<SSwitch checked={checked} onChange={setChecked} />
```
:::

## With Text

::: tabs vue3 vue2 react
@tab vue3

```vue
<SSwitch v-model="checked" activeText="ON" inactiveText="OFF" />
```

@tab vue2

```vue
<SSwitch v-model="checked" activeText="ON" inactiveText="OFF" />
```

@tab react

```tsx
<SSwitch checked={checked} onChange={setChecked} activeText="ON" inactiveText="OFF" />
```
:::

## Sizes

::: tabs vue3 vue2 react
@tab vue3

```vue
<SSwitch v-model="checked" size="large" />
<SSwitch v-model="checked" size="middle" />
<SSwitch v-model="checked" size="small" />
```

@tab vue2

```vue
<SSwitch v-model="checked" size="large" />
<SSwitch v-model="checked" size="middle" />
<SSwitch v-model="checked" size="small" />
```

@tab react

```tsx
<SSwitch checked={checked} onChange={setChecked} size="large" />
<SSwitch checked={checked} onChange={setChecked} size="middle" />
<SSwitch checked={checked} onChange={setChecked} size="small" />
```
:::

## Props

### Vue3 / Vue2 / React

| Name | Description | Type | Default |
|------|-------------|------|---------|
| modelValue / v-model / checked | Switch state | `boolean` | `false` |
| disabled | Disabled state | `boolean` | `false` |
| size | Switch size | `'large' \| 'middle' \| 'small'` | `'middle'` |
| activeColor | Active color | `string` | - |
| inactiveColor | Inactive color | `string` | - |
| activeText | Active text | `string` | - |
| inactiveText | Inactive text | `string` | - |

## Events

### Vue3 / Vue2

| Name | Description |
|------|-------------|
| change | Triggered when switch state changes |

### React

| Name | Description |
|------|-------------|
| onChange | Triggered when switch state changes |