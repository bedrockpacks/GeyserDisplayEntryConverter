<div align="center">

# 🧩 PackCrafter GeyserDisplayEntity Mapping Converter

### ⚡ Convert Nexo Furniture YAML Display Entity Mapping YAML instantly

[![Status](https://img.shields.io/badge/status-stable-orange)]()
[![Platform](https://img.shields.io/badge/platform-browser-lightgrey)]()
[![License](https://img.shields.io/badge/use-client%20utility-blue)]()

</div>

---

## ✨ Overview

**PackCrafter GeyserDisplayEntity Converter** is a lightweight browser tool designed to automatically generate  
separate **Display Entry Extension mapping files** from Nexo / Java furniture YAML.

It helps server owners and pack developers speed up large furniture pack workflows without manual mapping creation.

---

## 🚀 Features

✔ Drag & drop or upload ZIP  
✔ Generates separate mapping file for each furniture item  
✔ Skips invalid entries (missing material or custom model data)  
✔ Clean modern UI with dark mode support  
✔ Quick access button to Mapping Merge tool  

---

## 📦 Mapping Format Generated

Each furniture entry becomes:

```yaml
mappings:
  furniture_name:
    type: "minecraft:paper"
    model-data: 12345
    item-identifier: "none"
    displayentityoptions:
      y-offset: -0.5
      vanilla-scale: false
      vanilla-scale-multiplier: 1
      hand: false
