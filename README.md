# Xifres i Lletres · Laboratori Tecnopedagògic

[![Llicència Codi: AGPL v3](https://img.shields.io/badge/Llicència%20Codi-AGPL%20v3-blue.svg)](https://www.gnu.org/licenses/agpl-3.0.html)
[![Llicència Continguts: CC BY-SA 4.0](https://img.shields.io/badge/Continguts-CC%20BY--SA%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by-sa/4.0/)
[![Versió](https://img.shields.io/badge/Versió-1.2%20Stable-indigo.svg)](#)
[![Marc DUA](https://img.shields.io/badge/DUA-Universal%20Design%20for%20Learning-emerald.svg)](#)
[![Privacitat: 100% Client--Side](https://img.shields.io/badge/Privacitat-100%25%20Client--Side-teal.svg)](#)

> **Aplicació educativa interactiva de càlcul mental i enriquiment lèxic en llengua catalana**, basada en el marc DUA (*Disseny Universal per a l'Aprenentatge*) i dissenyada per a la dinamització d'aula amb Pantalles Digitals Interactives (PDI), ordinadors o tauletes.

---

## 🌐 Accés a l'Aplicació Web

Pots utilitzar l'aplicació immediatament des de qualsevol dispositiu sense necessitat d'instal·lació:

👉 **[Obrir Xifres i Lletres en línia](https://elcordones.github.io/xifres-i-lletres/)**

---

## 🎯 Enfocament Tecnopedagògic i Curricular

Aquest recurs adapta el format clàssic del concurs televisiu a la realitat pedagògica de l'aula del segle XXI, promovent:

1. **Competència en comunicació lingüística**:
   - Ampliació del vocabulari actiu i passiu en llengua catalana.
   - Reconeixement ortogràfic i fonològic (dígrafs, ce trencada `ç`, accents i dièresis).
   - Connexió directa amb el diccionari normatiu de l'Institut d'Estudis Catalans (**DIEC2**).

2. **Competència matemàtica i sentit numèric**:
   - Estratègies flexibles de càlcul mental i jerarquia d'operacions bàsiques (`+`, `−`, `×`, `÷`).
   - Estimació numèrica, aproximacions i valor posicional de les xifres.
   - Descomposició de problemes complexos en passos consecutius.

3. **Treball Cooperatiu i Convivència**:
   - Mode d'aula per equips (Equip Blau vs. Equip Vermell) amb torns alterns que afavoreixen la deliberació i la presa de decisions col·lectiva.

---

## ✨ Característiques Principals

### 🔤 1. Motor de Lletres (Llengua Catalana)
- **Bossa ponderada segons el corpus català**: Distribució de probabilitats adaptada a la freqüència d'aparició de vocals i consonants en català.
- **Corpus lèxic integrat**: Més de 3.000 entrades normatives validades per a una resposta instantània sense dependència de connexió a internet.
- **Validació Docent a l'Aula**: Si l'alumnat troba una paraula normativa no inclosa al corpus inicial, el mestre pot validar-la amb un sol clic i s'incorpora automàticament a la memòria de l'aula (`localStorage`).
- **Enllaços DIEC2 contextuals**: Cada paraula proposada o descoberta ofereix un enllaç directe a la seva definició oficial a l'IEC.
- **Normalització de diacrítics**: L'aplicació admet caràcters naturals preservant l'especificitat de la ce trencada (`ç`).
- **Suport fònic (Web Speech API)**: Lectura en veu alta en català (`ca-ES`) dels mots formats per reforçar la correspondència grafia-so.

### 🔢 2. Motor de Xifres (Sentit Numèric)
- **Objectius cognitivament adaptats**: En els nivells inicials es garanteix sempre l'existència matemàtica d'almenys una combinació exacta amb les xifres disponibles.
- **Interfície hàptica tàctil i responsiva**: Disseny de rajoles 3D (`tile-3d`) amb estats visuals clars (seleccionat, utilitzat, deshabilitat).
- **Motor algorítmic exhaustiu en arbre (DFS amb poda)**: Calcula en menys de 5 mil·lisegons la solució òptima i tots els passos necessaris per assolir el nombre diana.
- **Pista pedagògica de primer pas**: En lloc de donar la solució feta, proporciona una primera pista per desbloquejar el raonament de l'alumnat.
- **Demostració pas a pas**: En finalitzar la ronda, l'alumnat pot observar com el motor ha resolt el repte amb un desplegable visual pas a pas.

### 🧠 3. Marc DUA (Disseny Universal per a l'Aprenentatge) i Accessibilitat
- **Mode Zen (🧘)**: Suprimeix la pressió del cronòmetre per a un aprenentatge calmat, atenent a la diversitat i ritmes d'aprenentatge diferenciats (alumnat amb TDAH, TEA o altes necessitats de suport educatiu).
- **Pausa Docent (⏸️)**: El mestre pot aturar el rellotge en qualsevol instant per debatre estratègies col·lectivament davant la pissarra digital.
- **Dreceres de Teclat**: Possibilitat d'utilitzar el teclat físic de l'ordinador per introduir lletres, validar (`Enter`), esborrar (`Backspace`) o reiniciar (`Escape`).
- **Mode Clar / Fosc**: Adaptació cromàtica automàtica o manual per garantir màxim contrast i reduir la fatiga visual.

### 📊 4. Dinamització d'Aula i Avaluació Formativa
- **Mode Equips**: Puntuació separada i indicador visual de torn actiu per a dinamització competitiva sana o col·laborativa.
- **Quadern d'Avaluació**: Panell estadístic amb el resum complet de la sessió (rondes jugades, paraula més llarga, percentatge de càlculs exactes, precisió aritmètica).
- **Exportació i Impressió**: Botó de còpia ràpida del resum textual per al diari d'aula i funció directa d'impressió en paper o PDF.

---

## 🎚️ Nivells Educatius Disponibles

| Nivell | Edats orientatives | Característiques Lletres | Característiques Xifres |
| :--- | :--- | :--- | :--- |
| **Inicial** | 6 - 8 anys (CI) | 6 lletres · 60 s | Objectiu 10 - 50 (Solució exacta garantida) |
| **Mitjà** | 8 - 10 anys (CM) | 8 lletres · 50 s | Objectiu 20 - 150 (Operacions bàsiques) |
| **Avançat** | 10 - 14 anys (CS / ESO) | 9 lletres · 45 s | Objectiu 50 - 500 (Reglament estàndard) |
| **Expert** | +14 anys / Adults | 10 lletres · 40 s | Objectiu 100 - 999 (Format concurs TV) |

---

## 🔒 Privacitat i Seguretat de Dades

- **Arquitectura 100% Client-Side**: L'aplicació s'executa exclusivament al navegador de l'usuari.
- **Cap servidor extern de recollida de dades**: Ni les dades de sessió, ni els noms d'equips, ni les paraules afegides surten del dispositiu escolar.
- **Conforme al RGPD i a la normativa de protecció de dades a l'escola**.

---

## 💻 Stack Tecnològic i Execució Local

L'aplicació està concebuda com una **arquitectura monòlitica autònoma**: un únic fitxer HTML amb estils i lògica integrats, sense cap pas de compilació ni gestor de paquets (`npm`, `webpack`, etc.).

- **HTML5 & CSS3** amb [Tailwind CSS](https://tailwindcss.com/) (distribució CDN).
- **JavaScript pur (Vanilla ES6+)** sense dependències de frameworks.
- **Web Audio API**: Síntesi de freqüències i efectes acústics procedimentals directes.
- **Web Speech API**: Síntesi fònica nativa del sistema.
- **Google Fonts**: `Inter` i `Space Grotesk`.

### Executar en local
1. Clona el repositori:
   ```bash
   git clone https://github.com/elCordones/xifres-i-lletres.git
   ```
2. Obre directament el fitxer `index.html` amb qualsevol navegador web modern (Chrome, Firefox, Safari, Edge).

---

## 📄 Autoria i Llicenciament

- **Autoria pedagògica i desenvolupament**: **David Cordones** · 2026
- **Llicència de Codi**: [GNU Affero General Public License v3.0 (AGPL v3)](https://www.gnu.org/licenses/agpl-3.0.html)
- **Llicència de Continguts Educatius**: [Creative Commons Reconeixement-CompartirIgual 4.0 Internacional (CC BY-SA 4.0)](https://creativecommons.org/licenses/by-sa/4.0/)

---

*Projecte dissenyat per potenciar el gust per la llengua catalana i el pensament matemàtic a les aules.*
