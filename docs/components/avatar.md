# Avatar (https://zupy-ui.github.io/docs/components/avatar.md)

<Preview>
  <Avatar name="Maya Lin" size="sm" />
  <Avatar name="Sam Ortiz" />
  <Avatar name="Fox" fallback="🦊" size="lg" />
  <Avatar name="Robin Park" size="xl" shape="square" />
</Preview>

```tsx
import { Avatar } from "@zupy/ui";

<Avatar name="Maya Lin" src="/maya.png" />
<Avatar name="Fox" fallback="🦊" />
```

The image is shown once it loads. Until then, or if it fails, the fallback is shown: the initials of `name`, or whatever you pass as `fallback`.

## Props [#props]

| Prop       | Type                                  | Default        |
| ---------- | ------------------------------------- | -------------- |
| `name`     | `string`                              | required       |
| `src`      | `string`                              |                |
| `fallback` | `ReactNode`                           | initials       |
| `size`     | `"sm" \| "md" \| "lg" \| "xl"`        | `"md"`         |
| `shape`    | `"circle" \| "square"`                | `"circle"`     |
