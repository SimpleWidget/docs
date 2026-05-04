# Upload

File upload component.

## Basic Usage

::: tabs vue3 vue2 react
@tab vue3

```vue
<SUpload
  action="/api/upload"
  @success="handleSuccess"
  @error="handleError"
/>
```

@tab vue2

```vue
<SUpload
  action="/api/upload"
  @success="handleSuccess"
  @error="handleError"
/>
```

@tab react

```tsx
<SUpload
  action="/api/upload"
  onSuccess={handleSuccess}
  onError={handleError}
/>
```
:::

## Multiple Files

::: tabs vue3 vue2 react
@tab vue3

```vue
<SUpload
  action="/api/upload"
  multiple
  @success="handleSuccess"
/>
```

@tab vue2

```vue
<SUpload
  action="/api/upload"
  multiple
  @success="handleSuccess"
/>
```

@tab react

```tsx
<SUpload
  action="/api/upload"
  multiple
  onSuccess={handleSuccess}
/>
```
:::

## Props

### Vue3 / Vue2 / React

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

### Vue3 / Vue2

| Name | Description |
|------|-------------|
| success | Triggered on upload success |
| error | Triggered on upload error |
| progress | Triggered on upload progress |
| change | Triggered when file selection changes |

### React

| Name | Description |
|------|-------------|
| onSuccess | Triggered on upload success |
| onError | Triggered on upload error |
| onProgress | Triggered on upload progress |
| onChange | Triggered when file selection changes |