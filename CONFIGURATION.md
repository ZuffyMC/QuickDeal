# QuickDeal Configuration

QuickDeal is designed to be easy to manage and customize.

## Main Files

```txt
config.yml
categories.yml
sounds.yml
price-limits.yml
item-rules.yml
webhooks.yml
```

## Language Files

```txt
messages/english.yml
messages/indonesia.yml
```

## GUI Files

```txt
gui/dashboard.yml
gui/browse.yml
gui/sell_item.yml
gui/confirm_listing.yml
gui/buy_confirm.yml
gui/profile.yml
gui/leaderboard.yml
gui/rating.yml
gui/admin_dashboard.yml
```

## Example Settings

```yml
plugin:
  language: "english"

storage:
  type: "sqlite"

selling:
  enabled: true
  drag-and-drop: true
  chat-price-input: true
  confirm-before-listing: true
  return-item-on-close: true

backup:
  enabled: true
  auto-backup: true
  interval: "6h"
  keep-last: 10
```

## GUI Customization

Each GUI menu supports configurable title, size, items, materials, slots, names, lore, sounds, and actions.
