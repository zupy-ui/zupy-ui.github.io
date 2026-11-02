# Segmented (https://zupy-ui.github.io/docs/components/segmented.md)

<Preview>
  <Segmented defaultValue="week" aria-label="Range">
    <SegmentedItem value="day">Day</SegmentedItem>
    <SegmentedItem value="week">Week</SegmentedItem>
    <SegmentedItem value="month">Month</SegmentedItem>
  </Segmented>
</Preview>

```tsx
import { Segmented, SegmentedItem } from "@zupy/ui";

<Segmented defaultValue="week" aria-label="Range">
  <SegmentedItem value="day">Day</SegmentedItem>
  <SegmentedItem value="week">Week</SegmentedItem>
  <SegmentedItem value="month">Month</SegmentedItem>
</Segmented>
```

The selected item is raised in the primary color. Clicking the selected item again does nothing, so there is always a selection.

## Props [#props]

### Segmented [#segmented]

| Prop            | Type                      | Default        |
| --------------- | ------------------------- | -------------- |
| `value`         | `string`                  |                |
| `defaultValue`  | `string`                  |                |
| `onValueChange` | `(value: string) => void` |                |
| `orientation`   | `"horizontal" \| "vertical"` | `"horizontal"` |
| `disabled`      | `boolean`                 | `false`        |

### SegmentedItem [#segmenteditem]

| Prop       | Type      | Default  |
| ---------- | --------- | -------- |
| `value`    | `string`  | required |
| `disabled` | `boolean` | `false`  |

Built on [Base UI Toggle Group](https://base-ui.com/react/components/toggle-group).
