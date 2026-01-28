# AEGIS CS2 Panel

## Complete Management System for Counter-Strike 2 Communities

### Transform your CS2 community into a professional eSports experience

---

## Overview

**AEGIS CS2 Panel** is a complete and professional web platform for managing Counter-Strike 2 servers, players, matches, and tournaments. Developed for competitive communities, amateur leagues, and eSports organizations seeking a robust and scalable solution.

![Dashboard overview](docs/prints/home-dashboard.png)

### Key Highlights

- **60+ administrative features** for complete management
- **Advanced ranking system** based on individual performance
- **Native MatchZy integration** (market-leading plugin)
- **Responsive panel** with light/dark theme
- **Multi-language** (Portuguese and English)
- **External integrations** (Steam, Discord, LivePix)

---

## Main Features

### 1. Player Management

| Feature | Description |
|---------|-------------|
| **Complete Profiles** | Individual profiles with Steam ID, avatar, detailed statistics, and match history |
| **Reputation System** | Player evaluation after matches (likes/dislikes) |
| **Levels and Rankings** | Visual progression system with badges (Bronze, Silver, Gold, Platinum, etc.) |
| **Punishments** | Complete punishment system with types, periods, and history |
| **Skins Inventory** | Complete customization system (see dedicated section below) |
| **Comments** | Comment system on player profiles |

![Players list](docs/prints/players-1.png)
![Players list with filters](docs/prints/players-2.png)
![Player profile overview](docs/prints/profile.png)
![Player profile details](docs/prints/profile-2.png)
![Player search](docs/prints/search-players.png)

### 2. Match Management

| Feature | Description |
|---------|-------------|
| **Real-Time Monitoring** | Live match tracking with automatic updates |
| **Detailed Statistics** | K/D/A, damage, headshots, clutches, utilities, and more |
| **Complete History** | Record of all matches with advanced filters |
| **Multi-Map** | Support for BO1, BO3, and BO5 series |
| **Voting System** | Post-match player evaluation |

![Matches list](docs/prints/matches.png)
![Match details overview](docs/prints/matches-details-1.png)
![Match details stats](docs/prints/matches-details-2.png)

### 3. Ranking System

| Feature | Description |
|---------|-------------|
| **Smart Algorithm** | Calculation based on individual performance (not just win/loss) |
| **Configurable Weights** | KD (40%), Kills (25%), Assists (15%), Damage (15%), Headshots (5%) |
| **MVP Bonus** | +3 additional points for match MVP |
| **TVP System** | 2x point multiplier when active |
| **Leaderboards** | Global rankings with pagination and multiple views |
| **History** | Progression chart of the last 50 games |

![Leaderboard overview](docs/prints/ranking-1.png)
![Leaderboard detail view](docs/prints/ranking-2.png)

### 4. Series and Tournament Management

| Feature | Description |
|---------|-------------|
| **Guided Creation** | 5-step wizard for complete setup |
| **Map Pick/Ban** | Interactive interface for map veto |
| **Team Management** | Configuration of starters and substitutes |
| **MatchZy Integration** | Automatic configuration generation |
| **Discord Notifications** | Automatic series announcements |

![Series overview](docs/prints/series-1.png)
![Series creation step 1](docs/prints/series-create-1.png)
![Series creation step 2](docs/prints/series-create-2.png)
![Series creation step 3](docs/prints/series-create-3.png)
![Series creation step 3 (team setup)](docs/prints/series-create3-1.png)
![Series creation step 3 (roster)](docs/prints/series-create3-2.png)
![Series creation step 4](docs/prints/series-create4.png)
![Series creation step 4 (online)](docs/prints/series-create4-online.png)
![Series creation step 4 (online map)](docs/prints/series-create4-online-2.png)
![Series creation step 4 (offline)](docs/prints/series-create4-offline.png)
![Series creation step 5](docs/prints/series-create5-1.png)
![Series creation step 5 (match configuration)](docs/prints/series-create5-2.png)
![Series creation step 5 (summary)](docs/prints/series-create5-3.png)

### 5. Admin Panel

| Feature | Description |
|---------|-------------|
| **Centralized Dashboard** | Overview with quick access to all functions |
| **User Management** | Full CRUD for administrators and moderators |
| **Server Control** | RCON commands, real-time status, monitoring |
| **Notification System** | Creation and management of player announcements |
| **Feedback Management** | User suggestions and bug report center |
| **Maintenance Tools** | Ranking recalculation, migrations, data cleanup |

![System settings](docs/prints/settings.png)
![Server settings](docs/prints/settings-server.png)

### 6. Server Monitoring

| Feature | Description |
|---------|-------------|
| **Real-Time Status** | Current map, online players, capacity |
| **RCON Commands** | Remote server command execution |
| **Command History** | Log of all administrative actions |
| **Status Alerts** | Visual server health indicators |

### 7. Inventory and Skins System

The panel includes a **complete skin customization system** that allows players to customize their entire in-game appearance.

#### Item Categories

| Category | Description |
|----------|-------------|
| **Agents** | Custom characters for CT and T separately |
| **Knives** | All CS2 knife types with individual skins |
| **Gloves** | All available gloves with variations |
| **Pins** | Collectibles and event pins |
| **Music** | Music Kits to customize game sounds |
| **Colored Smokes** | Custom smoke effects (Premium) |
| **Pistols** | All pistols with their skins |
| **SMGs** | Customizable submachine guns |
| **Rifles** | Assault and precision rifles |
| **Heavy** | Machine guns and shotguns |

#### Inventory Features

| Feature | Description |
|---------|-------------|
| **Team Selection** | Configure different skins for CT and T |
| **Wear** | Fine adjustment of wear (FN, MW, FT, WW, BS) |
| **Seed (Pattern)** | Configure the skin's visual pattern (0-1000) |
| **Smart Search** | Find skins by name in real-time |
| **Visual Preview** | Preview the skin before applying |
| **Sorting** | By name or rarity |

![Inventory overview](docs/prints/inventory-1.png)
![Inventory item details](docs/prints/inventory-2.png)
![Inventory loadout view](docs/prints/inventory-3.png)

#### Loadouts System

| Feature | Description |
|---------|-------------|
| **Save Loadouts** | Save complete skin configurations |
| **Load Loadouts** | Apply a saved loadout with one click |
| **Export Loadouts** | Export as JSON file to share |
| **Import Loadouts** | Import loadouts from other players |
| **Loadout Preview** | View contents before applying |
| **Delete Loadouts** | Remove unused loadouts |

#### Additional Resources

| Feature | Description |
|---------|-------------|
| **Complete Reset** | Remove all customizations at once |
| **Statistics** | Counter of equipped skins, knives, gloves, agents |
| **Visual Indicators** | Badges showing items equipped by team |
| **Premium Content** | Exclusive items for subscribers (e.g., Smokes) |
| **Steam Integration** | Requires Steam account linking |

---

## Integrations

### Steam
- Steam OpenID authentication
- Automatic avatar import
- Steam ID validation
- Account linking

### Discord
- Notification webhooks
- Series/tournament announcements
- Custom embeds with team information
- Server status

### LivePix
- Donation wallet integration
- Stream goal tracking
- BRL (Brazilian Real) support

### MatchZy
- Automatic configuration generation
- Statistics synchronization
- Match data import
- Series export

---

## Interface and Experience

### Modern Design
- **Bootstrap 5.3.2** - Market-leading responsive framework
- **Mobile-First** - Optimized for mobile devices
- **Light/Dark Theme** - User preference saved automatically
- **Statistics Cards** - Clear metrics visualization
- **Smooth Animations** - Modern transitions and effects

![Light and dark theme](docs/prints/dark-light-mode.png)

### Intuitive Navigation
- Collapsible sidebar
- Menu organized by categories
- Breadcrumbs for orientation
- Quick shortcuts

### Accessibility
- Adequate contrast
- Readable font sizes
- Touch-friendly for mobile
- Informative tooltips

---

## Special Features

### Betting System
- Point betting between players
- Pending bet management
- Automatic resolution
- Complete history

### Seasons
- Season/semester system
- Prize tracking
- Award countdown
- Top 1 highlight

![Season overview](docs/prints/season.png)

### In-App Notifications
- System announcements
- Configurable priorities
- Read tracking
- Unread badge

---

## Security

| Feature | Implementation |
|---------|----------------|
| **CSRF Protection** | Tokens on all forms |
| **SQL Injection** | Prepared statements in all queries |
| **XSS** | Output sanitization and escaping |
| **Passwords** | Bcrypt hashing |
| **Sessions** | Secure management with timeout |
| **Access Control** | RBAC (Role-Based Access Control) |
| **Sensitive Variables** | Stored in .env |

---

## Technical Requirements

### Server
- PHP 7.4 or higher
- MySQL 5.7+ / MariaDB 10.3+
- Composer
- Apache or Nginx
- SSL recommended

### CS2
- Dedicated CS2 server
- MatchZy plugin installed
- RCON enabled

---

## Access Levels

| Level | Permissions |
|-------|-------------|
| **Admin** | Full system access |
| **Moderator** | Viewing and monitoring |
| **Player** | Profile, statistics, leaderboard |
| **User** | Public access only |

---

## Competitive Advantages

### Why choose AEGIS CS2 Panel?

1. **Complete Solution** - Everything you need in a single platform
2. **Fair Ranking** - Algorithm based on performance, not just wins
3. **Native Integration** - MatchZy, Steam, Discord already integrated
4. **Professional Code** - Clean and well-documented architecture
5. **Multi-language Support** - Native Portuguese and English
6. **Updates** - Continuous development with new features
7. **Customizable** - Adapt to your community's needs

---

## Use Cases

### Competitive Communities
Manage rankings, organize tournaments, and keep your community engaged with a professional progression system.

### Amateur Leagues
Organize championships with pick/ban system, BO3/BO5 series, and automatic MatchZy integration.

### eSports Organizations
Centralize management of multiple teams, players, and events on a single platform.

### Public Servers
Offer a differentiated experience with rankings, player profiles, and detailed statistics.

---

## System Statistics

- **60+** Administrative features
- **30+** Internal APIs
- **20+** Database tables
- **15+** Integrations and modules
- **2** Supported languages
- **4** Access levels

---

## Contact and Licensing

For information about licensing, customization, and support:

**[Insert contact information]**

---

## Screenshots

Screenshots are placed throughout the document in their respective sections.

---

**AEGIS CS2 Panel** - *Professional eSports Management Solution*

© 2024-2026 All Rights Reserved
