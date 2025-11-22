---
title: Announcement Block
description: Display important announcements and notices to your users with the Announcement block.
---

<InlineAlert variant="info" slots="text" />

Note: The Announcement block replaces the Teaser block that was previously used in Gatsby.

The Announcement Block allows you to display important notices, updates, or calls-to-action to your users. It can be customized with different variants, background colors, and positioning options.

## Available Options

- **Variants:** `primary` (bold, prominent) or `secondary` (subtle)
- **Background Colors:** `background-color-gray`, `background-color-white`
- **Slots:** `heading`, `text`, `button`
- **Position:** `center` (for button-only announcements)

## Variants

There are 2 main usage patterns:

- The [announcement with heading](announcement-with-heading.md) variant for full announcements with title, description, and action button.
- The [button-only announcement](announcement-button-only.md) variant for simple, centered call-to-action buttons.
