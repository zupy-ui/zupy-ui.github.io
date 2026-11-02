# Card (https://zupy-ui.github.io/docs/components/card.md)

<Preview>
  <ZupyCard className="w-64">
    <Heading level={3}>Weekly goal</Heading>
    <Text tone="muted" className="mt-1">Three of five days done.</Text>
  </ZupyCard>
  <ZupyCard variant="flat" className="w-64">
    <Heading level={3}>Flat</Heading>
    <Text tone="muted" className="mt-1">For content inside a raised card.</Text>
  </ZupyCard>
  <ZupyCard variant="sunken" className="w-64">
    <Heading level={3}>Sunken</Heading>
    <Text tone="muted" className="mt-1">A tinted area with no border.</Text>
  </ZupyCard>
</Preview>

```tsx
import { Card, Heading, Text } from "@zupy/ui";

<Card>
  <Heading level={3}>Weekly goal</Heading>
  <Text tone="muted">Three of five days done.</Text>
</Card>
```

## Props [#props]

| Prop      | Type                                   | Default    |
| --------- | -------------------------------------- | ---------- |
| `variant` | `"raised" \| "flat" \| "sunken"`       | `"raised"` |
| `padding` | `"none" \| "sm" \| "md" \| "lg"`       | `"md"`     |
| `render`  | `ReactElement`                         |            |
