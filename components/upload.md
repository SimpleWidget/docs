# Upload

File upload component.

## Basic Usage

```vue
<SUpload
  action="/api/upload"
  @success="handleSuccess"
  @error="handleError"
/>
```

## Props

| Name | Description | Type | Default |
|------|-------------|------|---------|
| action | Upload URL | `string` | - |
| method | Request method | `'post' \| 'put'` | `'post'` |
| headers | Request headers | `object` | - |
| data | Extra form data | `object` | - |
| name | File field name | `string` | `'file'` |
| accept | Accepted file types | `string` | - |
| multiple | Multiple files | `boolean` | `false` |
| disabled | Disabled state | `boolean` | `false` |
| autoUpload | Auto upload on select | `boolean` | `true` |

## Events

| Name | Description |
|------|-------------|
| success | Triggered on upload success |
| error | Triggered on upload error |
| progress | Triggered on upload progress |
| change | Triggered when file selection changes |