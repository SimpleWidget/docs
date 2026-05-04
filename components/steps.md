# Steps

Step progress indicator.

## Basic Usage

```vue
<SSteps :current="1">
  <SStepsItem title="Step 1" description="Description" />
  <SStepsItem title="Step 2" description="Description" />
  <SStepsItem title="Step 3" description="Description" />
</SSteps>
```

## Vertical

```vue
<SSteps direction="vertical" :current="1">
  <SStepsItem title="Step 1" description="Description" />
  <SStepsItem title="Step 2" description="Description" />
  <SStepsItem title="Step 3" description="Description" />
</SSteps>
```

## Props

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