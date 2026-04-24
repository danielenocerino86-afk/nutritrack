# 🥗 NutriTrack

Il tuo diario alimentare personale — PWA installabile.

## 🚀 Deploy su GitHub Pages

### Step 1 — Crea il repo
1. Vai su **github.com/new**
2. Nome repo: `nutritrack` (o come preferisci)
3. **Public**
4. Clicca **Create repository**

### Step 2 — Pusha i file
```bash
cd nutritrack-gh
git init
git add .
git commit -m "NutriTrack v3"
git branch -M main
git remote add origin https://github.com/TUO-USERNAME/nutritrack.git
git push -u origin main
```

### Step 3 — Attiva GitHub Pages
1. Vai su **Settings** del repo
2. Sidebar: **Pages**
3. Source: **Deploy from a branch**
4. Branch: **main** / cartella **/ (root)**
5. Clicca **Save**
6. Dopo circa 1 minuto il sito sara live su:
   `https://TUO-USERNAME.github.io/nutritrack/`

## 📱 Installare come App
- **Android**: Chrome → menu tre puntini → Installa app
- **iPhone**: Safari → condividi → Aggiungi alla schermata Home

## ✨ Funzionalita
- Onboarding step-by-step (nome, sesso, eta, altezza, peso, obiettivo, attivita)
- Calcolo automatico BMI, BMR, TDEE
- Piano alimentare con import da file del nutrizionista
- Lista spesa auto-generata
- Tracking peso e BMI con grafici
- Misurazioni corporee
- Tracker acqua
- Attivita fisica e diario giornaliero
- Funziona offline
- Export/import backup JSON
