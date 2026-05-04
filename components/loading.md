# Loading

Loading state component.

## Basic Usage

```vue
<SLoading v-model="loading" />
<div v-loading="loading">Content</div>
```

## Props

| Name | Description | Type | Default |
|------|-------------|------|---------|
| modelValue | Loading state | `boolean` | `false` |
| text | Loading text | `string` | `'Loading...'` |
| fullscreen | Full screen loading | `boolean` | `false` |
| background | Mask background | `string` | `'rgba(0,0,0,0.7)'` |

## Directives

| Name | Description |
|------|-------------|
| v-loading | Show loading overlay |