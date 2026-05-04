# Dropdown

Dropdown menu component.

## Basic Usage

::: tabs vue3 vue2 react
@tab vue3

```vue
<SDropdown>
  <SButton>Dropdown</SButton>
  <template #dropdown>
    <SDropdownItem @click="handleItem1">Item 1</SDropdownItem>
    <SDropdownItem @click="handleItem2">Item 2</SDropdownItem>
  </template>
</SDropdown>
```

@tab vue2

```vue
<SDropdown>
  <SButton>Dropdown</SButton>
  <template slot="dropdown">
    <SDropdownItem @click="handleItem1">Item 1</SDropdownItem>
    <SDropdownItem @click="handleItem2">Item 2</SDropdownItem>
  </template>
</SDropdown>
```

@tab react

```tsx
<SDropdown
  trigger={<SButton>Dropdown</SButton>}
  onItemClick={handleItemClick}
>
  <SDropdownItem command="item1">Item 1</SDropdownItem>
  <SDropdownItem command="item2">Item 2</SDropdownItem>
</SDropdown>
```
:::

## Click Trigger

::: tabs vue3 vue2 react
@tab vue3

```vue
<SDropdown trigger="click">
  <SButton>Click Me</SButton>
  <template #dropdown>
    <SDropdownItem>Item 1</SDropdownItem>
    <SDropdownItem>Item 2</SDropdownItem>
  </template>
</SDropdown>
```

@tab vue2

```vue
<SDropdown trigger="click">
  <SButton>Click Me</SButton>
  <template slot="dropdown">
    <SDropdownItem>Item 1</SDropdownItem>
    <SDropdownItem>Item 2</SDropdownItem>
  </template>
</SDropdown>
```

@tab react

```tsx
<SDropdown trigger="click">
  <SButton>Click Me</SButton>
  <SDropdownItem>Item 1</SDropdownItem>
  <SDropdownItem>Item 2</SDropdownItem>
</SDropdown>
```
:::

## Props

### Vue3 / Vue2 / React

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

### Vue3 / Vue2

| Name | Description |
|------|-------------|
| command | Triggered when item clicked |

### React

| Name | Description |
|------|-------------|
| onItemClick | Triggered when item clicked |