# Steps

Step progress indicator.

## Basic Usage

::: details Vue3

```vue
<SSteps :current="1">
  <SStepsItem title="Step 1" description="Description" />
  <SStepsItem title="Step 2" description="Description" />
  <SStepsItem title="Step 3" description="Description" />
</SSteps>
```

:::

::: details Vue2

```vue
<SSteps :current="1">
  <SStepsItem title="Step 1" description="Description" />
  <SStepsItem title="Step 2" description="Description" />
  <SStepsItem title="Step 3" description="Description" />
</SSteps>
```

:::

::: details React

```tsx
<SSteps current={1}>
  <SStepsItem title="Step 1" description="Description" />
  <SStepsItem title="Step 2" description="Description" />
  <SStepsItem title="Step 3" description="Description" />
</SSteps>
```

:::

## Props

| Name | Description | Type | Default |
|------|-------------|------|---------|
| current | Current step | `number` | `0` |
| direction | Step direction | `'horizontal' \| 'vertical'` | `'horizontal'` |
| size | Steps size | `'large' \| 'middle' \| 'small'` | `'middle'` |