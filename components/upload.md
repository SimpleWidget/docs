# Upload

File upload component.

## Basic Usage

::: details Vue3

```vue
<SUpload
  action="/api/upload"
  @success="handleSuccess"
  @error="handleError"
/>
```

:::

::: details Vue2

```vue
<SUpload
  action="/api/upload"
  @success="handleSuccess"
  @error="handleError"
/>
```

:::

::: details React

```tsx
<SUpload
  action="/api/upload"
  onSuccess={handleSuccess}
  onError={handleError}
/>
```

:::

## Props

| Name | Description | Type | Default |
|------|-------------|------|---------|
| action | Upload URL | `string` | - |
| method | Request method | `'post' \| 'put'` | `'post'` |
| multiple | Multiple files | `boolean` | `false` |
| disabled | Disabled state | `boolean` | `false` |

## Events

| Name | Description | Vue3 | Vue2 | React |
|------|-------------|------|------|-------|
| success | Upload success | `@success` | `@success` | `onSuccess` |
| error | Upload error | `@error` | `@error` | `onError` |
| progress | Upload progress | `@progress` | `@progress` | `onProgress` |