# CountDown

Countdown timer display.

## Basic Usage

```vue
<SCountDown :time="60000" @end="handleEnd" />
```

## Props

| Name | Description | Type | Default |
|------|-------------|------|---------|
| time | Time in milliseconds | `number` | `0` |
| format | Format string | `string` | `'HH:mm:ss'` |
| autoStart | Auto start countdown | `boolean` | `true` |

## Events

| Name | Description |
|------|-------------|
| end | Triggered when countdown ends |
| change | Triggered when time changes |

## React Props Difference

| Name | Description | Type | Default |
|------|-------------|------|---------|
| onEnd | End handler | `() => void` | - |
| onChange | Change handler | `(time: number) => void` | - |