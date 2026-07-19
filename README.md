# Animal Tracker Long Range

[![Version](https://img.shields.io/badge/version-1.1-brightgreen)](ModInfo.xml)
[![Game](https://img.shields.io/badge/7%20Days%20To%20Die-3.0%2B-blue)](https://7daystodie.com)
[![Mod](https://img.shields.io/badge/mod-XML%20only-orange)](Config/nav_objects.xml)

---

## 📋 Description

Increases the vanilla **Animal Tracker** on-screen icon detection range from **25 m to 100 m** in **7 Days to Die 3.0+**. Designed for players who disable the compass or play with minimal HUD. Also increases the offset of the icon above the creatures' heads so that they do not overlap their bodies.

The default game behavior requires you to get very close before the icon appears. This can be inconvenient for players who:

- disable the compass;
- play with minimal HUD settings;
- prefer a more immersive survival experience;
- want to use the Animal Tracker perk without constantly searching blindly.

> ⚠️ **Note:** This mod does **not** add new tracking mechanics and does **not** reveal animals on the map. It only increases the existing on-screen detection range of the vanilla Animal Tracker system.

---

## ✨ Features

- ✅ Increases Animal Tracker icon visibility distance
- ✅ Works with vanilla tracking mechanics
- ✅ **XML-only** — no DLL, no Harmony patches
- ✅ Lightweight and performance friendly
- ✅ Compatible with existing saves
- ✅ Easy to install and remove

---

## 📥 Installation

1. **Download** the archive.
2. **Extract** the folder `AnimalTrackerLongRange` into your 7 Days to Die Mods folder:

```
...\7 Days To Die\Mods\
```

3. **Your final structure** should look like:

```
7 Days To Die
└── Mods
    └── AnimalTrackerLongRange
        ├── ModInfo.xml
        └── Config
            └── nav_objects.xml
```

4. **Start the game.**

> ✅ No additional configuration is required.

---

## 🔧 Compatibility

- ✅ Tested for **7 Days to Die 3.0**
- ✅ Works in **singleplayer**
- 🌐 For **multiplayer servers**, the mod must be installed on the server
- ✅ Compatible with most mods **unless they also modify** `nav_objects.xml`

---

## ⚙️ Configuration

The default increased detection range is set to **100 meters**.

Advanced users can edit:

```
Config/nav_objects.xml
```

and change the `max_distance` value to their preferred distance.

---

## 🗑️ Removal

Simply delete:

```
Mods/AnimalTrackerLongRange
```

from your game folder.

> ✅ No save reset is required.

---

## 📜 Changelog

| Version | Changes |
|---------|---------|
| 1.1     | Added vertical offset adjustments so the icon no longer overlaps creature models |
| 1.0     | Initial release with increased detection range (25 m → 100 m), updated for game version 3.0 |

---

**Made with ❤️ for the 7 Days to Die community**