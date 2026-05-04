# Badge

Badge is used to display status or count.

## Basic Usage

::: tabs vue3 vue2 react
@tab vue3

```vue
<SBadge value="5">
  <div style="width: 40px; height: 40px; background: #f0f0f0;"></div>
</SBadge>
<SBadge value="99" />
<SBadge value="100" :max="99" />
```

@tab vue2

```vue
<SBadge value="5">
  <div style="width: 40px; height: 40px; background: #f0f0f0;"></div>
</SBadge>
<SBadge value="99" />
<SBadge :value="100" :max="99" />
```

@tab react

```tsx
<SBadge value="5">
  <div style={{width: 40, height: 40, background: '#f0f0f0'}}></div>
</SBadge>
<SBadge value="99" />
<SBadge value="100" max={99} />
```
:::

## Types

::: tabs vue3 vue2 react
@tab vue3

```vue
<SBadge value="5" type="primary" />
<SBadge value="5" type="success" />
<SBadge value="5" type="danger" />
<SBadge value="5" type="warning" />
<SBadge value="5" type="info" />
```

@tab vue2

```vue
<SBadge value="5" type="primary" />
<SBadge value="5" type="success" />
<SBadge value="5" type="danger" />
<SBadge value="5" type="warning" />
<SBadge value="5" type="info" />
```

@tab react

```tsx
<SBadge value="5" type="primary" />
<SBadge value="5" type="success" />
<SBadge value="5" type="danger" />
<SBadge value="5" type="warning" />
<SBadge value="5" type="info" />
```
:::

## Dot Mode

::: tabs vue3 vue2 react
@tab vue3

```vue
<SBadge dot type="primary" />
<SBadge dot type="success" />
```

@tab vue2

```vue
<SBadge dot type="primary" />
<SBadge dot type="success" />
```

@tab react

```tsx
<SBadge dot type="primary" />
<SBadge dot type="success" />
```
:::

## Props

### Vue3 / Vue2 / React

| Name | Description | Type | Default |
|------|-------------|------|---------|
| value | Badge value | `string \| number` | `''` |
| type | Badge type | `'primary' \| 'success' \| 'danger' \| 'warning' \| 'info'` | `'danger'` |
| max | Max value | `number` | `99` |
| dot | Dot mode | `boolean` | `false` |
| show | Show/hide | `boolean` | `true` |