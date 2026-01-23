# 📷 Camera Arena

**Aplicație web pentru gestionarea colecțiilor de aparate foto vintage**

![Version](https://img.shields.io/badge/version-2.0-blue)
![License](https://img.shields.io/badge/license-MIT-green)
![Platform](https://img.shields.io/badge/platform-web-orange)

---

## ✨ Descriere

Camera Arena este o aplicație completă pentru colecționarii de aparate foto. Funcționează 100% în browser, fără server, cu stocare locală în IndexedDB. Perfect pentru a cataloga, organiza și valorifica colecția ta de camere vintage.

---

## 🚀 Funcționalități

### 📋 Gestionare Colecție
- **Câmpuri complete**: Denumire, Marcă, Model, Tip (principal + secundar), An fabricație, Țară origine, Tip film, Raritate, Număr serie, Stare, Funcțional, Proveniență, Prețuri, Note
- **16 tipuri de aparate**: SLR Film, SLR Digital, Mirrorless, Rangefinder, TLR, Box Camera, Folding Camera, și altele
- **18 tipuri de film**: De la Plăci de sticlă la Digital, inclusiv formate rare (116, 122, 127, 828)
- **21 de țări** cu steaguri emoji (suport Twemoji pentru Chrome)
- **5 nivele de raritate** cu culori distinctive

### 🔍 Filtrare și Sortare
- Căutare text în denumire, marcă, model, note
- Filtrare după: Tip aparat, Tip film, Țară, Raritate
- Sortare după: An, Denumire, Marcă, Preț, Valoare catalog
- Filtrare duală pe tip (caută în Tip principal SAU secundar)

### 👁️ Vizualizare
- **3 moduri**: Tile (carduri mari), List (tabel), Compact (carduri mici)
- **Virtual scrolling** pentru colecții mari (100+ aparate)
- **Badges colorate** pentru Stare, Funcțional, Raritate, Țară

### 📊 Statistici
- Număr total aparate și mărci
- Valoare totală achiziție și catalog
- Statistici pentru selecția curentă (când sunt filtre active)

### 📤 Export
- **Excel (.xlsx)**: Export complet sau doar selecția filtrată
- **PDF Listă**: Tabel cu toate aparatele + statistici
- **PDF Fișă individuală**: Fișă profesională per aparat cu fotografie

### ⚙️ Personalizare
- **6 teme de culori**: Auriu, Albastru, Verde, Violet, Roșu, Teal
- **Mod Dark/Light**
- **Română / Engleză**
- **Nume proprietar** personalizabil (apare în exporturi)

### 💾 Stocare
- **IndexedDB** - stocare persistentă în browser
- **Backup/Restore JSON** - salvare și restaurare completă
- **Import Excel** - import în masă din fișiere existente
- **Compresie imagini** - automat la 800x800px, ~80KB

---

## 🖥️ Instalare

### Varianta simplă (recomandată)
1. Descarcă fișierul `camera-collection.html`
2. Deschide-l în browser (Chrome, Firefox, Edge)
3. Gata! Începe să adaugi aparate

### Din GitHub
```bash
git clone https://github.com/DanCalancea/camera-arena.git
cd camera-arena
# Deschide camera-collection.html în browser
```

---

## 📖 Utilizare

### Adăugare aparat
1. Click pe **"+ Adaugă Aparat"**
2. Completează câmpurile (Denumire, Marcă, Model sunt obligatorii)
3. Încarcă o fotografie (opțional)
4. Click **"Salvează"**

### Filtrare
- Folosește caseta de căutare pentru text
- Selectează din dropdown-uri pentru filtrare precisă
- Combină mai multe filtre simultan

### Export
- **Excel**: Click "Export Excel" - exportă selecția sau tot
- **PDF Listă**: Click "Export PDF" - generează catalog
- **PDF Fișă**: Click pe icona 📄 de pe fiecare aparat

### Backup
1. Deschide **Setări** (⚙️)
2. Click **"Salvează Backup"** pentru export JSON
3. Pentru restaurare: **"Restaurează"** și selectează fișierul

---

## 🛠️ Tehnologii

- **HTML5** - structură
- **CSS3** - stilizare (variabile CSS, flexbox, grid)
- **JavaScript ES6+** - logică aplicație
- **IndexedDB** - stocare persistentă
- **SheetJS (xlsx)** - export/import Excel
- **Twemoji** - steaguri cross-browser
- **Google Fonts** - Playfair Display, Source Sans 3

---

## 📁 Structură fișiere

```
camera-arena/
├── camera-collection.html    # Aplicația completă (single file)
├── README.md                 # Documentație
└── LICENSE                   # Licență MIT
```

---

## 🤝 Contribuții

Contribuțiile sunt binevenite! 

1. Fork repository-ul
2. Creează branch pentru feature (`git checkout -b feature/AmazingFeature`)
3. Commit modificările (`git commit -m 'Add AmazingFeature'`)
4. Push la branch (`git push origin feature/AmazingFeature`)
5. Deschide un Pull Request

---

## 📝 Licență

Distribuit sub licența MIT. Vezi `LICENSE` pentru mai multe informații.

---

## 👤 Autor

**Merlinlx**

---

## 🙏 Mulțumiri

- [SheetJS](https://sheetjs.com/) - pentru export/import Excel
- [Twemoji](https://twemoji.twitter.com/) - pentru emoji cross-browser
- [Google Fonts](https://fonts.google.com/) - pentru fonturi

---

## 📸 Screenshots

<img width="3200" height="1800" alt="{C60D6DDA-2670-4301-8410-E7DC2AE2B348}" src="https://github.com/user-attachments/assets/acc07170-8319-4a4e-a887-435859f14bf4" />

---

**⭐ Dacă îți place proiectul, lasă o stea pe GitHub!**
