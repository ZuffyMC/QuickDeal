<p align="center">
  <img src="assets/banner.png" alt="QuickDeal Banner" width="900">
</p>

<h1 align="center">QuickDeal Version 1.0</h1>

<p align="center">
  <b>Modern AuctionHouse & Marketplace Plugin for Minecraft Servers</b>
</p>

<p align="center">
  🛒 Marketplace GUI • 💰 Drag & Drop Selling • ⭐ Seller Ratings • 💾 Auto Backup • ⚙️ Fully Customizable
</p>

<p align="center">
  <a href="https://modrinth.com/plugin/quickdeal"><b>Download on Modrinth</b></a>
</p>

---

## 📌 About QuickDeal

**QuickDeal** is a modern Minecraft **AuctionHouse** plugin built to make server trading cleaner, safer, and easier to manage.

Instead of opening directly into a basic auction list, QuickDeal gives players a marketplace-style experience with a clean dashboard, player profiles, drag & drop selling, seller ratings, transaction history, expired item recovery, and admin tools.

QuickDeal is designed for survival, SMP, economy, roleplay, and community servers that want a professional trading system with a customizable GUI.

---

## ✨ Highlights

* 🏪 Modern marketplace-style dashboard
* 💰 Safe drag & drop item selling
* 🔢 Amount selector and price editor
* 💬 Chat-based custom price input
* ✅ Buy and sell confirmation menus
* 💸 Tax preview and final earning display
* ⭐ Seller rating and trust system
* 👤 Player market profiles with skin heads
* 🏆 Top seller leaderboard
* 📜 Purchase and sales history
* 📦 Expired item recovery
* 🎒 Pending claims for full inventories
* 🔔 Configurable broadcasts and notifications
* 🛠️ Admin control panel
* 🧾 Transaction logs
* 💾 Auto backup system
* 🎨 Fully customizable GUI
* 🌐 English and Indonesian language support
* 🔌 Vault economy bridge support
* 📊 PlaceholderAPI support
* 🗄️ SQLite and MySQL/MariaDB storage support
* 🖥️ Premium startup console with ASCII banner

---

## 💰 Drag & Drop Selling

QuickDeal includes a safe and interactive GUI-based selling system.

Players can drag an item into the sell slot, adjust the item amount, set the price using GUI buttons, or type a custom price through chat input. The sell menu also shows tax preview and final earnings before the listing is confirmed.

Items are safely returned when selling is cancelled, the GUI is closed, the player quits, the plugin reloads, or the plugin is disabled. If the inventory is full, the item can be saved into pending claims.

---

## 🔔 Notifications & Broadcasts

QuickDeal includes configurable player notifications and marketplace broadcasts.

Server owners can enable or disable listing broadcasts, purchase notifications, seller alerts, offline seller messages, actionbar messages, sounds, and expensive item announcements through the configuration files.

---

## 🛒 Marketplace Dashboard

QuickDeal opens with a clean dashboard instead of a basic item list.

Players can access:

* Browse Marketplace
* Sell Item
* My Listings
* Expired Items
* Purchase History
* Sales History
* Player Profile
* Seller Leaderboard
* Rating Menu
* Help Center

---

## 💰 Drag & Drop Selling

QuickDeal includes a GUI-based selling system.

Players can drag an item into the sell slot, set the item amount, set the price using buttons or chat input, preview tax and final earnings, then confirm the listing safely.

Items are safely returned when selling is cancelled, the GUI is closed, the player quits, or the plugin is disabled.

---

## ⭐ Seller Ratings

After a successful purchase, buyers can rate sellers.

Ratings help players identify trusted sellers and improve the marketplace experience. High-rated sellers can stand out more in the marketplace.

---

## 🛡️ Safe Transactions

QuickDeal is designed to reduce item loss and duplication risks.

Safety features include:

* Transaction validation
* Listing state checks
* Cancel protection
* Inventory full protection
* Pending claims
* Anti-dupe checks
* Safe item return system

---

## ⚙️ Fully Customizable

Server owners can customize almost everything:

* GUI titles
* GUI size
* Button slots
* Materials
* Item names
* Lore
* Sounds
* Messages
* Categories
* Taxes
* Limits
* Backup settings
* Notifications
* Startup console

---

## 📥 Download

Download QuickDeal from Modrinth:

https://modrinth.com/plugin/quickdeal

---

## 🎮 Commands

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

## 🔐 Permissions

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

## 📦 Requirements

| Requirement     | Version                                     |
| --------------- | ------------------------------------------- |
| Minecraft       | 1.21+                                       |
| Java            | 21+                                         |
| Server Software | Paper / Spigot                              |
| Economy         | Vault-compatible economy plugin recommended |

Paper is recommended for the best experience.

---

## 🔌 Supported Integrations

* Vault
* PlaceholderAPI
* PlayerPoints
* TokenManager
* CoinsEngine
* ItemsAdder
* Oraxen
* MMOItems

Integrations are optional and depend on your server setup.

---

## 🗂️ Configuration

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

## 🧩 Support

Found a bug or have a suggestion?

Please open a GitHub Issue and include:

* QuickDeal version
* Server version
* Java version
* Economy plugin
* Error logs
* Steps to reproduce

---

## 📄 Source Code Notice

This repository is used for QuickDeal documentation, issue tracking, and support.

The plugin source code may be private depending on the release model.
