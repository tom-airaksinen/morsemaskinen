# Morsemaskinen 📻

En webapp för att lära sig morsekod – byggd för iPhone och iPad (funkar i alla webbläsare).

**Appen:** https://tom-airaksinen.github.io/morsemaskinen/

## Vad kan den?

- **🎧 Träna lyssning** – appen spelar morse för en bokstav, du gissar vilken. Nio nivåer som låser upp fler bokstäver (även Å Ä Ö och siffror). Streak och konfetti!
- **🔘 Sändarnyckeln** – knacka morse själv på en stor knapp, appen översätter till text.
- **📖 Morse-alfabetet** – tryck på ett tecken och hör hur det låter.
- Tre hastigheter: 🐢 Lugn, 🐇 Mellan, ⚡ Blixt.

## Tips på iPhone/iPad

Öppna länken i Safari → Dela-knappen → **Lägg till på hemskärmen**, så blir det som en riktig app.

## Teknik

En enda `index.html` – ren HTML/CSS/JS med Web Audio API. Inga beroenden, inget bygge. Framsteg sparas lokalt i webbläsaren (localStorage).
