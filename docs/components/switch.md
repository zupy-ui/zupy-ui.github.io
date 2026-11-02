# Switch (https://zupy-ui.github.io/docs/components/switch.md)

<Preview>
  <div className="flex flex-col gap-3">
    <label className="flex items-center gap-3">
      <Switch defaultChecked />
      Notifications
    </label>
    <label className="flex items-center gap-3">
      <Switch />
      Reduce motion
    </label>
    <label className="flex items-center gap-3 text-muted">
      <Switch disabled />
      Disabled
    </label>
  </div>
</Preview>

```tsx
import { Switch } from "@zupy/ui";

<label className="flex items-center gap-3">
  <Switch defaultChecked />
  Notifications
</label>
```

Use a switch for settings that take effect right away. Use a [Checkbox](/docs/components/checkbox) for choices that are submitted with a form.

## Props [#props]

| Prop              | Type                         | Default |
| ----------------- | ---------------------------- | ------- |
| `checked`         | `boolean`                    |         |
| `defaultChecked`  | `boolean`                    | `false` |
| `onCheckedChange` | `(checked: boolean) => void` |         |
| `disabled`        | `boolean`                    | `false` |
| `name`            | `string`                     |         |

Built on [Base UI Switch](https://base-ui.com/react/components/switch).
