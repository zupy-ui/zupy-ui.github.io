# Icon Button (https://zupy-ui.github.io/docs/components/icon-button.md)

<Preview>
  <IconButton aria-label="Home">
    <HomeIcon />
  </IconButton>
  <IconButton aria-label="Like" variant="accent">
    <HeartIcon tone="danger" />
  </IconButton>
  <IconButton aria-label="Search" variant="secondary">
    <SearchIcon />
  </IconButton>
  <IconButton aria-label="Notifications" variant="ghost">
    <BellIcon />
  </IconButton>
</Preview>

```tsx
import { SearchIcon } from "@zupy/icons";
import { IconButton } from "@zupy/ui";

<IconButton aria-label="Search" variant="secondary">
  <SearchIcon />
</IconButton>
```

Any SVG icon works, including [zupy icons](/docs/icons) and Lucide.

`aria-label` is required, because an icon alone gives screen readers nothing to read. All other props match [Button](/docs/components/button).
