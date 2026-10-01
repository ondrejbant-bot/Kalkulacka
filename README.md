# 🎓 Výuková aplikace pro 9. třídu ZŠ: Kalkulačka výrazů & CERMAT testy

Kompletní výuková aplikace pro žáky 9. třídy základní školy zaměřená na **úpravu algebraických výrazů, zlomky, procenta, lineární rovnice** a **přípravu na přijímací zkoušky CERMAT (Matematika & Český jazyk)**.

---

## 🎨 Černobílo-oranžový moderní design
- **Černé pozadí (`#090a0f`)**: Hluboký tmavý podklad s ambientním oranžovým nádechem.
- **Bílé karty (`#ffffff`)**: Čistý kontrastní podklad pro zadání, didaktické kroky, testové otázky i historii výpočtů.
- **Výrazná oranžová (`#ff6b00`)**: Akcent pro akční tlačítka, aktivní režimy, klíče řešení, čísla kroků a zvýraznění výsledků.

---

## 🌟 Novinky v této verzi

### 1. Plynulé přepínací menu s animací (Kalkulačka ⟷ CERMAT testy)
- Vpravo nahoře v hlavičce jsou dvě tlačítka: **🧮 Kalkulačka** a **📚 CERMAT testy**.
- **Efekt vtáhnutí / morphingu**:
  - Při kliknutí na *CERMAT testy* se obsah kalkulačky plynule smrskne směrem do tlačítka a místo něj rozkvete sekce CERMAT testů.
  - Při kliknutí na *Kalkulačka* se animace obrátí a aplikace se hladce vrátí zpět do kalkulačky.

### 2. Sekce přijímacích testů CERMAT (Matematika & Český jazyk)
- Přehled testů seřazených podle let (**2024, 2023, 2022, 2021, 2020**) a termínů (1. a 2. řádný termín).
- **Filtry**: Možnost filtrovat podle předmětu (*Matematika*, *Český jazyk*, *Vše*) i podle konkrétních roků.
- **Prohlížeč testu (👁️ Zobrazit test)**: Otevře interaktivní okno se zadáním úloh, bodovým ohodnocením a pokyny.
- **Tlačítko Tisk (🖨️)**: U každého testu lze jedním kliknutím připravit čistý tisk na papír A4 (vhodné pro zkušební nácvik na čas).
- **Klíč řešení (🔑)**: Možnost odkrýt správná řešení a postupy k ověření výsledků.
- **Propojení s kalkulačkou**: U matematických úloh je tlačítko *„🚀 Otevřít a spočítat v kalkulačce“*, které výraz automaticky přenese do kalkulačky a ukáže postup krok za krokem!

### 3. Vylepšená kalkulačka výrazů a rovnic
- **Zlomky**: Výrazy a rovnice se zlomky (`1/2x`, `3/4x`, `(2x - 1)/3`), převod na společného jmenovatele.
- **Procenta**: Zápisy `15% z x`, procentní změna `x + 20%`, samostatná procenta `50%`.
- **Lineární rovnice**: Automatické rozpoznání rovnítka `=`, odstranění zlomků, ekvivalentní úpravy a kompletní zkouška $L = P$.
- **Panel historie**:
  - Umístěn na pravé straně.
  - Kliknutím na položku se příklad znovu načte a spočítá.
  - Tlačítko **„🗑️ Vymazat historii“** pro smazání všech záznamů.
  - Uloženo v `localStorage` (lokální pro daný prohlížeč/zařízení – při spuštění z flashky na jiném PC bude historie čistá).

---

## 🚀 Jak spustit
- **V Google Chrome:** Dvakrát klikněte na [`Spustit_v_Chrome.bat`](./Spustit_v_Chrome.bat)
- **V Mozilla Firefoxu:** Dvakrát klikněte na [`Spustit_v_Firefoxu.bat`](./Spustit_v_Firefoxu.bat)
- **Ve výchozím prohlížeči:** Dvakrát klikněte na [`index.html`](./index.html)
