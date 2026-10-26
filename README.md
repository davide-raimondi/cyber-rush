# 🚀 Cyber Rush: Overdrive HD

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![Platform](https://img.shields.io/badge/Platform-Mobile%20%7C%20Web-blue?style=for-the-badge)
![License](https://img.shields.io/badge/License-MIT-green?style=for-the-badge)

**Cyber Rush: Overdrive HD** è un action-runner spaziale frenetico a 3 corsie sviluppato interamente in un **singolo file** (`index.html`), senza asset grafici o sonori esterni. Include combattimento automatico, battaglie contro boss titanici, generazione procedurale di settori e un hangar con navicelle e potenziamenti persistenti.

---

## 🎮 Funzionalità Principali

- **Movimento a 3 Corsie Meccanico:** Cambio corsia immediato con virata prospettica 3D della fusoliera e zero bagliori fastidiosi.
- **Sistema di Combattimento Automatico:** Cannoni al plasma con cadenza di fuoco continua. Allineati nella corsia dei droni per abbatterli e raccogliere gemme.
- **Battaglie Dreadnought:** Scontro con corazzate giganti a fine settore dotate di barre salute dedicate e telemetri laser ad alto rischio.
- **Super EMP (Onda d'Urto):** Carica l'indicatore energetico con kill e gemme per scatenare un'onda elettromagnetica che pulisce l'intero schermo.
- **Moltiplicatore Combo & Sfiorata:** Schivare gli ostacoli all'ultimo istante attiva il moltiplicatore di punteggio fino a 5x.
- **Motore Sprite HD Vettoriale:** Grafica dettagliata generata in-engine tramite SVG multistrato con ombre, cockpit traslucidi e feedback di colpo (*hit-flash*).
- **Audio Sintetizzato Nativo:** Effetti sonori dinamici a 8-bit/synth generati in tempo reale tramite **Web Audio API** (nessun file audio esterno da caricare).
- **Hangar & Economia Persistente:** 5 navicelle con armamenti specifici (fuoco rapido, doppio danno, laser quadruplo) e 3 moduli tecnologici potenziabili fino al livello 10 salvati in `localStorage`.

---

## 🕹️ Controlli

| Azione | Controllo Touch (Mobile) |
| :--- | :--- |
| **Sposta a Sinistra** | Tocco sulla metà sinistra dello schermo |
| **Sposta a Destra** | Tocco sulla metà destra dello schermo |
| **Attiva Super EMP** | Tocco sul pulsante circolare 🌩️ (quando carico al 100%) |
| **Pausa** | Tocco sul pulsante ⏸️ in alto a destra |

---

## 🛸 Flotta Navicelle

| Modello | Armamento / Abilità | Costo |
| :--- | :--- | :--- |
| **Valkyrie X1** | Doppio Cannone Plasma Standard | *Predefinito* |
| **Crimson Viper** | Cadenza di fuoco aumentata del 25% | 💎 3.500 |
| **Solaris Prime** | Proiettili Solari a Danno Doppio (x2) | 💎 12.000 |
| **Omega Wraith** | Triplo Cannone al Plasma a Ventaglio | 💎 35.000 |
| **Celestial Apex** | Quadruplo Laser Divino + Scudo Attivo all'Avvio | 💎 85.000 |

---

## 🛠️ Tecnologie Utilizzate

- **HTML5 Canvas API:** Rendering vettoriale 2D fluido a 60 FPS ottimizzato per display Retina/HiDPI.
- **Web Audio API:** Sintesi sonora procedurale di spari, impatti, laser ed esplosioni.
- **LocalStorage API:** Persistenza per record, gemme accumulate, navicelle sbloccate e upgrade.
- **CSS3 Glassmorphism:** Interfaccia mobile-first moderna con sfocature in tempo reale e layout adattivo.

---

## 📦 Installazione e Avvio Locale

Non servono build tool, Node.js o pacchetti esterni:

```bash
git clone [https://github.com/davide23567/cyber-rush.git](https://github.com/davide23567/cyber-rush.git)
cd cyber-rush
