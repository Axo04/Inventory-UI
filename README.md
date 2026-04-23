# Inventory UI (Web)

A simple, customizable inventory UI built with HTML, CSS, and JavaScript.

This project is meant to be a base system / sandbox that anyone can edit, expand, and remix.

---

## ✨ Features
- Click items to view stats
- Rarity-based color + glow system
- Enchant system with effects
- Clean layout (inventory → info panel)
- No frameworks, easy to edit

---

## 🚀 Getting Started
1. Download or clone this repository
2. Open newtab.html in your browser
3. Click items to interact with the UI

---

## 🛠️ Customization

### ➤ Add a New Item
Open newtab.html, copy one of the existing item elements, and change the values inside showItem().

Example:
<div class="item" onclick="showItem('Void Blade', 90, 'Void', 200)">
    <img src="voidblade.png">
</div>

---

### ➤ Add a New Rarity
Open script.js and find the rarityColors object.

Add a new entry like:
voidplus: "#FF2E8F"

Then use "VoidPlus" as the rarity in your item.

---

### ➤ Add a New Enchant
In script.js, find the enchant logic and add a new condition like:

else if (text.includes("Poison")) {
    title.textContent = "Poison";
    desc.textContent = "Deals damage over time";
    icon.src = "poison.png";
}

Then add it to the dropdown in newtab.html:
<option value="8">Poison (+8)</option>

---

## 🧪 What This Project Is
- UI prototype
- Inventory / loot sandbox
- Base for experiments

## ❌ What This Project Is Not
- A full game
- A polished release
- A finished system

---

## 📦 Make Your Own Version
Feel free to:
- Change the UI
- Add features
- Expand systems
- Completely redesign it

---

## 📢 Showcase
If you make something cool:
- Send it to me
- Or share your GitHub fork

Would be cool to see what people build

---

## 🔮 Future Idea
If enough people make different versions,
we might combine ideas into one bigger system

---

## 📄 Notes
- Code is intentionally simple and readable
- Some parts are basic on purpose (easy to edit)
- Focus is flexibility, not perfection

---

Have fun messing with it
