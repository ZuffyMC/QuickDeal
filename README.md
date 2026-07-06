<p align="center">
  <img src="assets/banner.png" alt="QuickDeal Banner" width="900">
</p>

<h1 align="center">QuickDeal v1.0</h1>

<p align="center">
  <b>Modern AuctionHouse & Marketplace Plugin for Minecraft Servers</b>
</p>

<p align="center">
  Marketplace GUI • Drag & Drop Selling • Seller Ratings • Auto Backup • Fully Customizable
</p>

---

## About QuickDeal

**QuickDeal** is a modern Minecraft AuctionHouse plugin built to make server trading cleaner, safer, and easier to manage.

Instead of opening directly into a basic item list, QuickDeal provides a marketplace-style dashboard where players can browse items, sell items with drag & drop, manage listings, view profiles, check seller ratings, and track their trading history.

QuickDeal is designed for survival, SMP, economy, roleplay, and community servers that need a clean and professional trading system.

---

## Highlights

- Modern marketplace-style dashboard
- Safe drag & drop item selling
- Buy and sell confirmation menus
- Seller rating and trust system
- Player market profiles
- Top seller leaderboard
- Purchase and sales history
- Expired item recovery
- Pending claims for full inventories
- Admin control panel
- Transaction logs
- Auto backup system
- Fully customizable GUI
- English and Indonesian language support
- Vault economy support
- PlaceholderAPI support
- SQLite and MySQL/MariaDB storage support

---

## Features

### Marketplace Dashboard

QuickDeal opens with a clean dashboard instead of a basic listing page.

Players can access Browse Marketplace, Sell Item, My Listings, Expired Items, Purchase History, Sales History, Player Profile, Seller Leaderboard, Rating Menu, and Help Center.

### Drag & Drop Selling

QuickDeal includes a GUI-based selling system.

Players can drag an item into the sell slot, set item amount, set price using buttons or chat input, preview tax and final earnings, then confirm or cancel safely.

Items are safely returned when selling is cancelled, the GUI is closed, the player quits, or the plugin is disabled.

### Seller Ratings

After a successful purchase, buyers can rate sellers. Ratings help players identify trusted sellers and improve the marketplace experience.

### Safe Transactions

QuickDeal is designed to reduce item loss and duplication risks with transaction validation, listing state checks, cancel protection, inventory full protection, pending claims, and anti-dupe checks.

### Fully Customizable

Server owners can customize GUI titles, GUI size, button slots, materials, item names, lore, sounds, messages, categories, taxes, limits, backup settings, notifications, and startup console.

---

## Commands

### Player Commands

```txt
/ah
/ah browse
/ah sell
/ah sell <price>
/ah listings
/ah expired
/ah sold
/ah history
/ah profile
/ah profile <player>
/ah leaderboard
/ah rating
/ah claims
/ah help
```

Aliases:

```txt
/quickdeal
/auctionhouse
/auction
/qd
/deal
```

### Admin Commands

```txt
/qda
/qda reload
/qda backup create
/qda backup list
/qda backup restore <file>
/qda listings
/qda listings <player>
/qda remove <listingId>
/qda logs
/qda logs <player>
/qda debug
/qda storage status
/qda economy status
/qda testdata <amount>
```

More details are available in [COMMANDS.md](COMMANDS.md).

---

## Permissions

Basic permissions:

```txt
quickdeal.use
quickdeal.open
quickdeal.sell
quickdeal.buy
quickdeal.cancel
quickdeal.history
quickdeal.profile
quickdeal.rating
quickdeal.leaderboard
quickdeal.claims
quickdeal.admin
```

More details are available in [PERMISSIONS.md](PERMISSIONS.md).

---

## Requirements

| Requirement | Version |
|---|---|
| Minecraft | 1.21+ |
| Java | 21+ |
| Server Software | Paper / Spigot |
| Economy | Vault-compatible economy plugin recommended |

Paper is recommended for the best experience.

---

## Supported Integrations

- Vault
- PlaceholderAPI
- PlayerPoints
- TokenManager
- CoinsEngine
- ItemsAdder
- Oraxen
- MMOItems

Integrations are optional and depend on your server setup.

---

## Configuration

QuickDeal generates its files inside:

```txt
plugins/QuickDeal/
```

Example structure:

```txt
plugins/QuickDeal/
├── config.yml
├── categories.yml
├── sounds.yml
├── price-limits.yml
├── item-rules.yml
├── webhooks.yml
├── database/
├── backups/
├── messages/
│   ├── english.yml
│   └── indonesia.yml
└── gui/
    ├── dashboard.yml
    ├── browse.yml
    ├── sell_item.yml
    ├── confirm_listing.yml
    ├── buy_confirm.yml
    ├── profile.yml
    ├── leaderboard.yml
    ├── rating.yml
    └── admin_dashboard.yml
```

More details are available in [CONFIGURATION.md](CONFIGURATION.md).

---

## Screenshots

Add screenshots to:

```txt
assets/screenshots/
```

---

## Support

Found a bug or have a suggestion? Please open a GitHub Issue and include your QuickDeal version, server version, Java version, economy plugin, error logs, and steps to reproduce.

---

## Source Code Notice

This repository is used for QuickDeal documentation, issue tracking, and support.

The plugin source code may be private depending on the release model.
