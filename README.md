## Länk till GitHub-repo
[https://github.com/bugstile/Portfolio](https://github.com/bugstile/Portfolio)

Du behöver inte öppna länken för att börja med instruktionerna.

### Instruktioner:

1. **Öppna Visual Studio Code**.
2. **Öppna terminalen** inuti Visual Studio Code (finns längst upp).  
   - **Kortkommando**: `Ctrl + Shift + Ö`
3. **Byt terminal till Git Bash**.  
   - Standardterminalen är PowerShell, vi vill ha Git Bash.  
   - Klicka på den lilla pilen uppe till höger i terminalen och välj Git Bash.
4. **Klona projektet**:  
   Skriv följande kommando i terminalen:  
   ```bash
   git clone https://github.com/bugstile/Portfolio.git
   ```
   - Nu har du kopierat projektet.  
5. Öppna `index.html`-filen i explorer med t.ex. Google Chrome.
   - Annars går det att öppna direkt i Visual Studio Code med hjälp av en extension vid namn **Live Server**.  
   - Om det är installerat, finns en knapp längst ner till höger som heter "Go Live".  
   - Klicka på den så bör hemsidan dyka upp i din standardwebbläsare.
  
  ### Navigation:
  För att navigera hemsidan finns det en navbar längst ner i footern. Det finns två sidor:  
  Hem och Kontakt.

### Kortfattad teknisk beskrivning:
- Webbplatsen uppfyller alla krav. Det finns en hemsida och en undersida.
  
- En konsekvent navigationsmeny som länkar mellan sidorna.
  
- Semantiska element har använts som `header`, `article`, `aside`, `section`, `figure`, `footer`, `nav`.
  
- Det finns media i `.webp`-format i CSS-grid portfoliogalleriet.
  
- Strukturen för hemsidan är till största delen byggd med hjälp av **flexbox**.
  
- `clamp()` har använts för text, letter-spacing och line-height.
  
- **Media queries** har använts för att anpassa utseendet, främst för större skärmar.
  
- HTML och CSS följer god praxis, men det finns alltid förbättringsområden.
  
- Webbplatsen är fullt responsiv.
  
- Det finns `alt`-attribut, `aria-labels`, titlar, `tab-index` och liknande.
  
- **Lighthouse** gav 100/100 på allt utom prestanda (bilder bör optimeras vidare).
  
- Inspektörläget har använts flitigt för att felsöka, testa och koda CSS.
  
- **WAVE** har använts för att förbättra semantiken markant; enligt WAVE är hemsidan nästan felfri.
  
- Git har använts, med två branches: `develop` och `main`.
  
- Arbetet utfördes primärt i `develop` och mergades till `main` när allt var klart.
