# Steps

Step progress indicator.

## Basic Usage

::: tabs vue3 vue2 react
@tab vue3

```vue
<SSteps :current="1">
  <SStepsItem title="Step 1" description="Description" />
  <SStepsItem title="Step 2" description="Description" />
  <SStepsItem title="Step 3" description="Description" />
</SSteps>
```

@tab vue2

```vue
<SSteps :current="1">
  <SStepsItem title="Step 1" description="Description" />
  <SStepsItem title="Step 2" description="Description" />
  <SStepsItem title="Step 3" description="Description" />
</SSteps>
```

@tab react

```tsx
<SSteps current={1}>
  <SStepsItem title="Step 1" description="Description" />
  <SStepsItem title="Step 2" description="Description" />
  <SStepsItem title="Step 3" description="Description" />
</SSteps>
```
:::

## Vertical

::: tabs vue3 vue2 react
@tab vue3

```vue
<SSteps direction="vertical" :current="1">
  <SStepsItem title="Step 1" description="Description" />
  <SStepsItem title="Step 2" description="Description" />
  <SStepsItem title="Step 3" description="Description" />
</SSteps>
```

@tab vue2

```vue
<SSteps direction="vertical" :current="1">
  <SStepsItem title="Step 1" description="Description" />
  <SStepsItem title="Step 2" description="Description" />
  <SStepsItem title="Step 3" description="Description" />
</SSteps>
```

@tab react

```tsx
<SSteps direction="vertical" current={1}>
  <SStepsItem title="Step 1" description="Description" />
  <SStepsItem title="Step 2" description="Description" />
  <SStepsItem title="Step 3" description="Description" />
</SSteps>
```
:::

## Props

### Vue3 / Vue2 / React

| Name | Description | Type | Default |
|------|-------------|------|---------|
| current | Current step | `number` | `0` |
| direction | Step direction | `'horizontal' \| 'vertical'` | `'horizontal'` |
| size | Steps size | `'large' \| 'middle' \| 'small'` | `'middle'` |

### StepsItem Props

| Name | Description | Type | Default |
|------|-------------|------|---------|
| title | Step title | `string` | - |
| description | Step description | `string` | - |
| icon | Step icon | `string` | - |