# BackTop

Scroll back to top of page.

## Basic Usage

```vue
<SBackTop />
```

## Custom Content

```vue
<SBackTop>
  <div>Top</div>
</SBackTop>
```

## Props

| Name | Description | Type | Default |
|------|-------------|------|---------|
| target | Scroll container selector | `string` | - |
| visibilityHeight | Show when scroll distance | `number` | `200` |
| duration | Scroll duration (ms) | `number` | `400` |