# Dropdown

Dropdown menu component.

## Basic Usage

::: details Vue3

```vue
<SDropdown>
  <SButton>Dropdown</SButton>
  <template #dropdown>
    <SDropdownItem @click="handleItem1">Item 1</SDropdownItem>
    <SDropdownItem @click="handleItem2">Item 2</SDropdownItem>
  </template>
</SDropdown>
```

:::

::: details Vue2

```vue
<SDropdown>
  <SButton>Dropdown</SButton>
  <template slot="dropdown">
    <SDropdownItem @click="handleItem1">Item 1</SDropdownItem>
    <SDropdownItem @click="handleItem2">Item 2</SDropdownItem>
  </template>
</SDropdown>
```

:::

::: details React

```tsx
<SDropdown trigger={<SButton>Dropdown</SButton>}>
  <SDropdownItem onClick={handleItem1}>Item 1</SDropdownItem>
  <SDropdownItem onClick={handleItem2}>Item 2</SDropdownItem>
</SDropdown>
```

:::

## Props

| Name | Description | Type | Default |
|------|-------------|------|---------|
| trigger | Trigger mode | `'hover' \| 'click'` | `'hover'` |

## Events

| Name | Description | Vue3 | Vue2 | React |
|------|-------------|------|------|-------|
| command | Item click | `@command` | `@command` | `onClick` |