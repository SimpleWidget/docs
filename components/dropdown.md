# Dropdown

Dropdown menu component.

## Basic Usage

```vue
<SDropdown>
  <SButton>Dropdown</SButton>
  <template #dropdown>
    <SDropdownItem @click="handleItem1">Item 1</SDropdownItem>
    <SDropdownItem @click="handleItem2">Item 2</SDropdownItem>
  </template>
</SDropdown>
```

## Click Trigger

```vue
<SDropdown trigger="click">
  <SButton>Click Me</SButton>
  <template #dropdown>
    <SDropdownItem>Item 1</SDropdownItem>
    <SDropdownItem>Item 2</SDropdownItem>
  </template>
</SDropdown>
```

## Props

| Name | Description | Type | Default |
|------|-------------|------|---------|
| trigger | Trigger mode | `'hover' \| 'click'` | `'hover'` |
| placement | Menu placement | `string` | `'bottom'` |

### DropdownItem Props

| Name | Description | Type | Default |
|------|-------------|------|---------|
| command | Command identifier | `string` | - |
| disabled | Disabled state | `boolean` | `false` |
| divided | Show divider | `boolean` | `false` |

## Events

| Name | Description |
|------|-------------|
| command | Triggered when item clicked |