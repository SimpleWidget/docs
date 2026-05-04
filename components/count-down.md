# CountDown

Countdown timer display.

## Basic Usage

::: details Vue3

```vue
<SCountDown :time="60000" @end="handleEnd" />
```

:::

::: details Vue2

```vue
<SCountDown :time="60000" @end="handleEnd" />
```

:::

::: details React

```tsx
<SCountDown time={60000} onEnd={handleEnd} />
```

:::

## Props

| Name | Description | Type | Default |
|------|-------------|------|---------|
| time | Time in milliseconds | `number` | `0` |
| format | Format string | `string` | `'HH:mm:ss'` |
| autoStart | Auto start countdown | `boolean` | `true` |

## Events

| Name | Description | Vue3 | Vue2 | React |
|------|-------------|------|------|-------|
| end | Countdown end | `@end` | `@end` | `onEnd` |
| change | Time change | `@change` | `@change` | `onChange` |