# 🛡️ Experimental RU Adlists

A curated collection of rule-sets for **Shadowrocket**, **Surge**, and **Stash**, focused on Russian ad-blocking, Apple infrastructure, and network privacy.

---

## 📋 Available Lists

| Icon | List Name | Purpose | Suggested Policy |
| :--- | :--- | :--- | :--- |
| 🚫 | **RU Ads & Trackers** | Russian advertising and tracking domains | `REJECT` |
| 🍏 | **Apple All** | Apple services and infrastructure | `DIRECT` / `PROXY` |
| 🚫 | **RU uBlock Origin** | Russian uBlock Origin filter rules | `REJECT` |
| 📡 | **Multicast & Special-IP** | Local multicast/broadcast & special-use IP ranges | `REJECT` (or `DIRECT`) |

---

## 📥 Copyable Links

> **Note:** jsDelivr (CDN) links are faster and cached. Raw links are fallback.

### 🚫 RU Ads & Trackers
- **jsDelivr (CDN):**  
  `https://cdn.jsdelivr.net/gh/pr0x77/experimental-ru-adslists@main/rules/ru-ads.txt`
- **raw (fallback):**  
  `https://raw.githubusercontent.com/pr0x77/experimental-ru-adslists/main/rules/ru-ads.txt`

### 🍏 Apple All
- **jsDelivr (CDN):**  
  `https://cdn.jsdelivr.net/gh/pr0x77/experimental-ru-adslists@main/rules/apple-all.txt`
- **raw (fallback):**  
  `https://raw.githubusercontent.com/pr0x77/experimental-ru-adslists/main/rules/apple-all.txt`

### 🚫 RU uBlock Origin
- **jsDelivr (CDN):**  
  `https://cdn.jsdelivr.net/gh/pr0x77/experimental-ru-adslists@main/rules/RuBlock-Origin.txt`
- **raw (fallback):**  
  `https://raw.githubusercontent.com/pr0x77/experimental-ru-adslists/main/rules/RuBlock-Origin.txt`

### 📡 Multicast & Special-IP
- **jsDelivr (CDN):**
  ```
  https://cdn.jsdelivr.net/gh/pr0x77/experimental-ru-adslists@main/rules/multicast.list
  ```
  
- **raw (fallback):**
```
  https://raw.githubusercontent.com/pr0x77/experimental-ru-adslists/main/rules/multicast.list
```

---

## 💡 Usage Example (Shadowrocket)

Add this line to your main configuration file (`.conf`):

```text
RULE-SET,https://cdn.jsdelivr.net/gh/pr0x77/experimental-ru-adslists@main/rules/multicast.list,REJECT
