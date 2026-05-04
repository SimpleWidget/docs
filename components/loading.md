# Loading

Loading state component.

## Basic Usage

```vue
<SLoading v-model="loading" />
<div v-loading="loading">Content</div>
```

## Fullscreen

```vue
<SLoading fullscreen />
```

## Props

| Name | Description | Type | Default |
|------|-------------|------|---------|
| modelValue / v-model | Loading state | `boolean` | `false` |
| text | Loading text | `string` | `'Loading...'` |
| fullscreen | Full screen loading | `boolean` | `false` |
| background | Mask background | `string` | `'rgba(0,0,0,0.7)'` |