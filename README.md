# GeyserDisplayEntryConverter
<div align="center">

# 🧩 PackCrafter — GeyserDisplayEntity Converter

### ⚡ Convert Nexo Furniture YAML → Display Entity Mapping YAML instantly

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

## 🚀 Key Features

✔ Drag & drop ZIP upload  
✔ Click-to-upload support  
✔ Generates **one mapping per furniture item**  
✔ Automatic namespace material conversion  
✔ Bulk ZIP export of mappings  
✔ Skipped entry detection system  
✔ Live mapping counter  
✔ Dark mode with memory  
✔ Smooth cursor glow interaction  
✔ Modern SaaS-style UI  
✔ Direct shortcut to Mapping Merge tool  

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
