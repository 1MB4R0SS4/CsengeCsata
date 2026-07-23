# ✏️ CsengeCSATA! (FirkaFUTAM)

> **A pörgős rajzolós társasjáték digitális asszisztense, kártyasorsolója és pontozója egyetlen intelligens webalkalmazásban.**

[![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/HTML)
[![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat&logo=css3&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/CSS)
[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

---

## 📖 A projektről

A **CsengeCSATA!** (vagy *FirkaFUTAM*) egy böngészőből futtatható, egyoldalas (Single-Page) webes alkalmazás, amely a népszerű rajzolós társasjáték menetét segíti és automatizálja. Kiváltja vagy kiegészíti a fizikai kártyapaklit, a dobókockát és a papíralapú pontozást, miközben játékos és firkált (doodle) stílusú felületet biztosít a játékosok számára.

---

## ✨ Főbb funkciók

* 🎴 **Kártyasorsoló & Szóválasztó:** 
  * Véletlenszerű kártyahúzás az adatbázisból.
  * Körönkénti kitaláló automatikus nyilvántartása.
  * Feladványok kiválasztása és jelölése.
* 🎲 **Interaktív Dobókocka:** 
  * Animált, fizikai hatású kockadobás a rárajzolt szimbólum kipörgetéséhez (melyre a rajzolónak „STOP!”-ot kell kiáltania).
* 👥 **Játékos- és Pontkezelő:**
  * 3–7 játékos támogatása.
  * **Drag & Drop** (fogd és vidd) sorrendezés a játékosok átrendezéséhez.
  * Körönkénti pontozás és automatikus győztes-kihirdetés a pakli elfogyásakor.
* 📜 **Előzmények követése:** 
  * A kisorsolt kártyák, kiválasztott szavak és pontszerzők visszakövethető listája.
* 📝 **Testreszabható Kártyaadatbázis:**
  * Beépített (közel 60 kártyás / 400+ szavas) gyári adatbázis.
  * Saját `.txt` fájlok betöltése, meglévő adatbázishoz való hozzáfűzése vagy élő szerkesztése.
  * Automatikus mentés a böngésző helyi tárolójába (`localStorage`).
* 📖 **Digitális Szabálykönyv:** 
  * Beépített, bármikor elérhető játékszabályzat a játék áttekintéséhez.
* 🎨 **Egyedi Visual Style:**
  * Játékos, rajzolt/firkált papírstílus (Google Fonts: *Caveat* és *Shantell Sans*), responsive elrendezéssel mobilra és asztali gépre egyaránt.

---

## 🛠️ Felhasznált technológiák

* **Frontend:** HTML5, CSS3 (CSS Variables, Flexbox, CSS Grid, Custom SVG Animations)
* **Logic:** Vanilla JavaScript (ES6+)
* **APIs & Storage:** HTML5 Drag and Drop API, FileReader API, LocalStorage API
* **Külső függőségek:** *Nincsenek!* A projekt keretrendszerektől mentes, így azonnal, telepítés nélkül fut bármelyik modern böngészőben.

---

## 🚀 Használat és futtatás

Nem igényel szerveroldali telepítést vagy `npm install`-t!

1. **Klónozd vagy töltsd le a tárolót:**
   ```bash
   git clone https://github.com/1MB4R0SS4/CsengeCsata
