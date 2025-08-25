<div align="center">
 
# 🎲 Yakyak

### *Game balance testing sandbox*
 
[![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)](https://python.org)
[![WebGL](https://img.shields.io/badge/WebGL-990000?style=for-the-badge&logo=webgl&logoColor=white)](https://www.khronos.org/webgl/)
[![SQLite](https://img.shields.io/badge/SQLite-003B57?style=for-the-badge&logo=sqlite&logoColor=white)](https://sqlite.org)

*Test balance changes in a sandbox environment*

---

## ⚙️ Core Mechanics Support

<table>
<tr>
<td align="center" width="33%">

### ⚔️ Combat Systems
Damage formulas & mitigation  
Attack speed & cooldowns  
Crit & dodge mechanics

</td>
<td align="center" width="33%">

### 💎 Resource Management  
Mana/energy systems  
Generation & consumption  
Cost curves & ratios

</td>
<td align="center" width="33%">

### 📈 Character Progression
Level scaling & power curves  
Skill trees & unlocks  
Item stats & bonuses

</td>
</tr>
</table>

---

## 🎮 Genre Templates

<table>
<tr>
<td align="center">

### 🗡️ MOBA
Heroes, abilities, items  
Map objectives

</td>
<td align="center">

### 🃏 Card Games
Deck building, mana curves  
Card effects

</td>
<td align="center">

### 🏰 RTS
Unit stats, build orders  
Resource rates

</td>
</tr>
<tr>
<td align="center">

### 🐉 RPG
Character stats, loot tables  
XP curves

</td>
<td align="center">

### 👊 Fighting
Frame data, combos  
Damage scaling

</td>
<td align="center">

### 🔫 Battle Royale
Weapon stats, zone damage  
Loot distribution

</td>
</tr>
</table>

---

## 📊 Analysis Features

```
Import → Modify → Simulate → Analyze → Export
  ↓        ↓         ↓          ↓        ↓
[JSON]  [Editor]  [Engine]  [Charts]  [Report]
```

**🔬 Simulation Engine** • Monte Carlo simulations • Win rate calculations • Matchup analysis • Meta emergence patterns

---

## 💻 Tech Stack

```javascript
const stack = {
  frontend: ["React", "WebGL", "D3.js"],
  backend: ["Python", "FastAPI", "NumPy"],
  database: ["SQLite", "Redis"],
  analysis: ["Pandas", "SciPy", "Monte Carlo"]
};
```

---

## 🚀 Development

```bash
# Setup
git clone https://github.com/gaba-dev/yakyak.git
cd yakyak

# Install dependencies
npm install
pip install -r requirements.txt

# Configure
cp .env.example .env

# Run
npm run dev
python backend/server.py
```

---

## 📋 Requirements

[![Node.js](https://img.shields.io/badge/Node.js_18+-339933?style=for-the-badge&logo=node.js&logoColor=white)](https://nodejs.org)
[![Python](https://img.shields.io/badge/Python_3.9+-3776AB?style=for-the-badge&logo=python&logoColor=white)](https://python.org)
[![RAM](https://img.shields.io/badge/RAM_4GB+-FF6B6B?style=for-the-badge&logo=memory&logoColor=white)]()

---

[![Documentation](https://img.shields.io/badge/Documentation-3776AB?style=for-the-badge&logo=gitbook&logoColor=white)](https://docs.yakyak.dev)

</div>

<div align="center">
   
# ⚔️ Legends Hold
### *Idle tower defense with famous heroes*

[![Idle Strategy](https://img.shields.io/badge/Idle_Strategy-059669?style=for-the-badge&logo=target&logoColor=white)]() 
[![Tower Defense](https://img.shields.io/badge/Tower_Defense-0EA5E9?style=for-the-badge&logo=shield&logoColor=white)]() 
[![Historical Heroes](https://img.shields.io/badge/Historical_Heroes-6B46C1?style=for-the-badge&logo=crown&logoColor=white)]() 

**🏰 Build** → **⚔️ Battle** → **📈 Upgrade** → **🌍 Expand**

---

## 🌍 Civilizations

<table>
<tr>
<td align="center" width="33%">

### 🏺 **Egyptian Empire**
[![Ancient Power](https://img.shields.io/badge/Ancient_Power-D97706?style=for-the-badge&logo=pyramid&logoColor=white)]()

**Heroes:** Cleopatra • Imhotep • Ancient Pharaohs  
**Style:** Sand-stone temples → Golden pyramid complexes  
**Special:** Hieroglyphic magic & sphinx guardians

</td>
<td align="center" width="33%">

### ⚔️ **Norse Kingdom**
[![Viking Fury](https://img.shields.io/badge/Viking_Fury-DC2626?style=for-the-badge&logo=axe&logoColor=white)]()

**Heroes:** Thor • Erik the Red • Viking Berserkers  
**Style:** Wooden longhouses → Epic stone halls  
**Special:** Runic powers & dragon-carved architecture

</td>
<td align="center" width="33%">

### 🏯 **Feudal Japan**
[![Samurai Honor](https://img.shields.io/badge/Samurai_Honor-059669?style=for-the-badge&logo=torii-gate&logoColor=white)]()

**Heroes:** Miyamoto Musashi • Oda Nobunaga • Legendary Samurai  
**Style:** Bamboo huts → Ornate pagoda castles  
**Special:** Cherry blossom gardens & precision strikes

</td>
</tr>
</table>

---

## 🏰 **Base Mode** *(Chill Building)*

<table align="center">
<tr>
<td align="center" width="50%">

### **🏛️ Main Hall**
*Unlock building evolution tiers*

**10 Models:** Humble hut → Grand palace  
**Function:** Gates progression system  
**Visual:** Civilization-specific architecture

</td>
<td align="center" width="50%">

### **🛡️ Barracks**
*Spawn legendary heroes*

**10 Models:** Basic training ground → Elite academy  
**Function:** Hero recruitment center  
**Visual:** Matches civilization aesthetic

</td>
</tr>
<tr>
<td align="center">

### **⚔️ Armory**
*Civilization-specific gear*

**10 Models:** Simple workshop → Master forge  
**Function:** Equipment upgrades  
**Visual:** Cultural weapon displays

</td>
<td align="center">

### **💰 Treasury**
*Idle gold generation*

**10 Models:** Coin pouch → Treasure vault  
**Function:** Passive income  
**Visual:** Growing wealth displays

</td>
</tr>
<tr>
<td align="center" colspan="2">

### **🗿 Monuments**
*Unique civilization bonuses*

**Egyptian:** Sphinx guardians • **Norse:** Runic obelisks • **Japanese:** Sacred shrines  
**Function:** Special passive abilities and combat bonuses

</td>
</tr>
</table>

---

## ⚔️ **War Mode** *(Tower Defense)*

```javascript
const gameplay = {
  deployment: ["Drag heroes to positions", "Strategic placement matters"],
  combat: ["Heroes auto-fight enemies", "Tap portraits for special attacks"],
  progression: ["Collect loot drops", "Defend your monuments"],
  victory: ["Win resources", "Unlock new content"]
};
```

### **🎯 Core Mechanics**
- **Simple Controls:** Drag-and-drop hero deployment
- **Active Abilities:** One-tap special moves per hero
- **Resource Collection:** Automatic loot pickup
- **Monument Defense:** Protect your civilization's wonders

---

## 🔄 **Core Loop**

**🏗️ Base Building** generates resources → **⚔️ War Mode** earns upgrades → **📈 Stronger Base** unlocks new content → **🔁 Repeat**

### **🎮 Target Audience**
Players who want strategic gameplay without overwhelming complexity

---

## ✨ **Key Features**

[![Visual Evolution](https://img.shields.io/badge/Visual_Evolution-4C1D95?style=for-the-badge&logo=trending-up&logoColor=white)]()
[![Famous Heroes](https://img.shields.io/badge/Famous_Heroes-7C2D12?style=for-the-badge&logo=users&logoColor=white)]()
[![Clean Design](https://img.shields.io/badge/Clean_Design-059669?style=for-the-badge&logo=palette&logoColor=white)]()

**🏛️ Building Evolution:** Watch civilization transform through 10 architectural stages  
**👥 Legendary Heroes:** Deploy famous historical figures with unique abilities  
**🎨 Clean Presentation:** Smooth gameplay with polished visual design

</div>
