# Radio (https://zupy-ui.github.io/docs/components/radio.md)

<Preview>
  <RadioGroup defaultValue="monthly" aria-label="Billing">
    <label className="flex items-center gap-2.5">
      <Radio value="monthly" />
      Monthly
    </label>
    <label className="flex items-center gap-2.5">
      <Radio value="yearly" />
      Yearly
    </label>
    <label className="flex items-center gap-2.5 text-muted">
      <Radio value="lifetime" disabled />
      Lifetime
    </label>
  </RadioGroup>
</Preview>

```tsx
import { Radio, RadioGroup } from "@zupy/ui";

<RadioGroup defaultValue="monthly" aria-label="Billing">
  <label className="flex items-center gap-2.5">
    <Radio value="monthly" /> Monthly
  </label>
  <label className="flex items-center gap-2.5">
    <Radio value="yearly" /> Yearly
  </label>
</RadioGroup>
```

## Props [#props]

### RadioGroup [#radiogroup]

| Prop            | Type                       | Default |
| --------------- | -------------------------- | ------- |
| `value`         | `string`                   |         |
| `defaultValue`  | `string`                   |         |
| `onValueChange` | `(value: string) => void`  |         |
| `disabled`      | `boolean`                  | `false` |
| `name`          | `string`                   |         |

### Radio [#radio]

| Prop       | Type      | Default  |
| ---------- | --------- | -------- |
| `value`    | `string`  | required |
| `disabled` | `boolean` | `false`  |

Built on [Base UI Radio Group](https://base-ui.com/react/components/radio).
