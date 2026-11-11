<div align="center">

# 記憶 &nbsp;Kioku

### *Your anime, kept in memory.*

A desktop anime info and watch tracker with a huge offline database,<br>
smart filters, personal ratings and recommendations built from your own taste.

<br>

![Platform](https://img.shields.io/badge/platform-Windows-0078D6?style=for-the-badge&logo=windows&logoColor=white)
![Built with Tauri](https://img.shields.io/badge/built%20with-Tauri-FFC131?style=for-the-badge&logo=tauri&logoColor=white)
![Rust](https://img.shields.io/badge/Rust-backend-000000?style=for-the-badge&logo=rust&logoColor=white)
![License](https://img.shields.io/badge/license-proprietary-red?style=for-the-badge)

<br>

[**⬇ Download Latest Release**](https://github.com/Overlord15/kioku-release/releases/latest)

<br>

<!-- 📸 HERO SCREENSHOT: replace the line below with  ![Kioku](screenshots/hero.png)  -->
> 📸 *Main screenshot goes here*

</div>

---

## ✨ What is Kioku?

**Kioku** (記憶) is Japanese for *memory*, and that is the idea behind the app: a place that remembers every anime you have seen, planned, dropped or loved.

Kioku ships with no heavy online dependency for browsing. It works from a **local database** that lives on your own machine, so searching, filtering and scrolling through thousands of titles stays fast. When you want fresh data, built-in Python scripts update the database for you, whenever *you* decide.

---

## 🧭 Features at a Glance

| | Feature | What it does |
|---|---|---|
| 🏠 | **Home** | Every anime in one alphabetical list, from special characters to Z |
| 🔎 | **Browse** | Filter by season, year, genre, studio and format |
| 📺 | **Watchlist** | Track what you are watching, plan to watch, or dropped |
| ⭐ | **Rated** | Everything you have ever rated, in one place |
| 🏆 | **Showcase** | A read-only gallery of your rated anime |
| 💡 | **For You** | Recommendations based on the anime you scored highly |
| ⚙️ | **Settings** | Set up and update your database |
| 🔄 | **Refresh button** | Reloads the app's data right after an update finishes |

---

## 🖼️ Tour

### 🏠 Home
Browse the complete library, sorted alphabetically from special characters through **A to Z**.

<!-- 📸 Replace with: ![Home](screenshots/home.png) -->
> 📸 *Home screenshot goes here*

<br>

### 🔎 Browse
Narrow thousands of titles down to exactly what you are in the mood for. Combine filters freely:

- **Season** and **Year**
- **Genre**
- **Studio**
- **Format:** TV, OVA and more

<!-- 📸 Replace with: ![Browse](screenshots/browse.png) -->
> 📸 *Browse screenshot goes here*

<br>

### 📺 Watchlist
Give every anime a status and see them grouped by it:

`Watching` · `Plan to Watch` · `Completed` · `Dropped` and more

<!-- 📸 Replace with: ![Watchlist](screenshots/watchlist.png) -->
> 📸 *Watchlist screenshot goes here*

<br>

### ⭐ Rated
Every anime you have scored, collected on a single page, so you can always look back at what you thought.

<!-- 📸 Replace with: ![Rated](screenshots/rated.png) -->
> 📸 *Rated screenshot goes here*

<br>

### 🏆 Showcase
A clean, **read-only** view of your rated anime. It is made for looking at and showing off, so nothing here can be edited by accident.

<!-- 📸 Replace with: ![Showcase](screenshots/showcase.png) -->
> 📸 *Showcase screenshot goes here*

<br>

### 💡 For You
Kioku learns from your taste. Rate some anime **7 out of 10 or higher** and this tab starts suggesting titles similar to the ones you enjoyed.

> ℹ️ You need to rate at least a few anime 7/10 or above before suggestions appear.

<!-- 📸 Replace with: ![For You](screenshots/foryou.png) -->
> 📸 *For You screenshot goes here*

<br>

### ⚙️ Settings
This is where the database is set up and kept up to date. See [Setting up the database](#-setting-up-the-database) below.

<!-- 📸 Replace with: ![Settings](screenshots/settings.png) -->
> 📸 *Settings screenshot goes here*

<br>

### 🔄 Floating Refresh Button
After a database update finishes, tap the floating **Refresh** button to reload the app with the new data. No restart needed.

<!-- 📸 Replace with: ![Refresh](screenshots/refresh.png) -->
> 📸 *Refresh button screenshot goes here*

---

## 🗄️ Setting up the database

Kioku needs a starting database, which is large (about **5 GB or more**), so it is downloaded separately from the app. On first launch, open **Settings** and pick whichever of the three options suits you:

| Option | Best when | What happens |
|---|---|---|
| 📦 **Choose ZIP file** | You downloaded the database zip manually | Kioku unpacks it into its install folder and uses it as the database |
| 🔗 **Paste ZIP link** | You have a direct link to the zip | Kioku downloads it, unpacks it, and uses it as the database |
| 📁 **Choose existing folder** | You already have the extracted files | Kioku simply points to that folder, with nothing copied |

> 💡 Whichever option you use, the update scripts always run against the folder that is set as your database, so everything stays consistent.

### Keeping it fresh

Kioku includes embedded **Python** scripts that collect new and updated anime data and write it into your database. You do **not** need to install Python yourself, because it ships inside the app. Updates run only **when you ask for them**, never in the background.

---

## 📥 Installation

1. Go to the [**Releases**](https://github.com/Overlord15/kioku-release/releases/latest) page.
2. Download the latest `Kioku_x.x.x_x64-setup.exe`.
3. Run the installer and follow the steps.
4. Open Kioku, go to **Settings**, and set up your database as described above.

**Requirements**
- Windows 10 or 11 (64-bit)
- Disk space for the database (5 GB or more)
- An internet connection for the optional link download and database updates

---

## 🛠️ Built With

- [**Tauri**](https://tauri.app) with a **Rust** backend
- **HTML, CSS and JavaScript** frontend
- **Python** (embedded) for data collection and database updates

---

## 📜 License

Kioku is **proprietary software**, free for **personal, non-commercial use**. Redistribution, modification and reverse engineering are not permitted. The full terms are included with every [release](https://github.com/Overlord15/kioku-release/releases/latest).

---

## ⚠️ Disclaimer

Kioku is an independent project and is not affiliated with, endorsed by, or connected to any anime streaming service, database or rights holder. All anime titles, artwork and related data belong to their respective owners.

---

<div align="center">

Made with care for anime fans &nbsp;·&nbsp; **記憶**, *to keep in memory*

</div>
