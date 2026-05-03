🏪 GC-Shops — Dynamic Shop System for QBCore

Create, manage, and own shops entirely in-game. No config editing. No restarts. Just /createshop and go.

SHOWCASE: https://youtu.be/oafQwWOeLdc

✨ Features

🛒 Buy Shops — Players browse and purchase items via ped or zone interaction
💰 Sell / Pawn Shops — Players sell inventory items for instant cash payouts
🥤 Vending Machines — Auto-detected from world props on first boot, quarters only
🏬 Player-Owned Storefronts — Assign any shop to a player by CitizenID with earnings tracking and withdrawal
💵 Multi-Currency Support — Cash, bank, or any custom ox_inventory item as currency
🪙 Quarter Economy — Cent-level pricing with automatic change-making
📦 Stock Management — Infinite or limited stock per item, with optional paid restocking
🔐 Server-Authority — Every purchase, sale, and payment validated server-side only
🎯 ox_target Integration — Ped and zone targeting, no button spam
⚡ Zero Config Setup — All shops created and managed in-game through menus


🔧 Dependencies

QBCore
ox_lib
ox_inventory
ox_target
oxmysql


📋 Commands
CommandPermissionDescription/createshopAdminCreate a shop at your current position/shopmanagerAdmin / OwnerManage the nearest shop/reloadshopsAdminForce reload all shops from database/getcid [id]AdminLook up a player's CitizenID by server ID/managemyshopShop OwnerOpen your owner dashboard

🏪 Shop Types
TypeDescription🛒 Buy ShopPlayers purchase items with cash, bank, or custom currency💸 Sell ShopPlayers sell items from their inventory to the shop🥤 Vending MachineAuto-registered world props, quarters-only payment🏬 Player-OwnedAny shop with an assigned owner who earns a cut of every sale

🪙 Quarter System
Vending machines auto use quarter_money is if you have it as an item. If you would like to change it you can totally customize it or you can just create your own shops if trying to avoid change.

🔐 Security

All transactions processed and validated server-side
ACE permission locking for all admin commands
Input sanitization and type validation on every net event
Vending machine scan rate-limited to one submission per session
Shop ownership verified against CitizenID on every owner action


⚙️ server.cfg
ensure GC-shops
add_ace group.admin gc.shops allow

🗄️ Installation

Drop GC-shops into your resources folder
Import sql/gc_shops_install.sql into your database
Add the lines above to server.cfg
Boot up and use /createshop in-game

For assistance with the script you can create a ticket at: https://discord.gg/SgxcTWHZ
Thanks for all the support, don't forget to buy me a coffee! buymeacoffee.com/GhostcoreScripts

Ghost Core Scripts
