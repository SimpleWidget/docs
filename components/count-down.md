# CountDown

Countdown timer display.

## Basic Usage

::: tabs vue3 vue2 react
@tab vue3

```vue
<SCountDown :time="60000" @end="handleEnd" />
```

@tab vue2

```vue
<SCountDown :time="60000" @end="handleEnd" />
```

@tab react

```tsx
<SCountDown time={60000} onEnd={handleEnd} />
```
:::

## Props

### Vue3 / Vue2 / React

| Name | Description | Type | Default |
|------|-------------|------|---------|
| time | Time in milliseconds | `number` | `0` |
| format | Format string | `string` | `'HH:mm:ss'` |
| autoStart | Auto start countdown | `boolean` | `true` |

## Events

### Vue3 / Vue2

| Name | Description |
|------|-------------|
| end | Triggered when countdown ends |
| change | Triggered when time changes |

### React

| Name | Description |
|------|-------------|
| onEnd | Triggered when countdown ends |
| onChange | Triggered when time changes |