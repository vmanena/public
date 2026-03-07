# Jak vložit soubory swf do Moodlu
Tento postup vám umožní vložit do Moodlu soubory ve formátu swf tak, že si uživatelé budou moci prohlížet jejich obsah bez instalování přehrávače nebo rozšíření prohlížeče. **V Moodlu ani na straně uživatele není potřeba nic instalovat.**

Využívá k tomu zdarma dostupný emulátor [ruffle](https://ruffle.rs/), který vložený flashový soubor ve formátu swf převede na html5. Uživateli se stránka zobrazí stejně jako běžný obsah.

 ## Postup vložení souboru
 Tento návod předpokládá, že soubor s Flashem má název **soubor.swf**. Pokud chcete použít jiný název, upravte ho v souboru **prehravac.html**.
 
    <div style="width:60%; aspect-ratio:5/4;">
      <embed src="soubor.swf" style="width:100%; height:100%;">
    </div>
 
 ### Krok 1 – Přidání materiálu Soubor
 
 Přidejte do kurzu studijní materiál **Soubor**
 
 ![Přidat studijní materiál soubor](moodle_ruffle_1.png)

### Krok 2 – Nahrání swf a přehrávače
Nahrajte soubor swf a prehravac.html.

![Nahrání souborů](moodle_ruffle_2.png)

### Krok 3 - Nastavení přehrávače jako hlavního souboru
Klikněte na **prehravac.html** a v dialogu ho nastavte jako hlavní. Studijní materiál uložte.

![Nastavení hlavního souboru](moodle_ruffle_3.png)

### Krok 4 – Vyzkoušení a případné úpravy
Vyzkoušejte, jestli se soubor zobrazuje správně. Většina materiálů ve formátu swf by se měla správně zobrazovat s hodnotami, které jsou nastaveny v přehrávači. Pokud by byl materiál zdeformovaný, můžete zkusit změnit poměr stran. Kromě 5/4 používaly materiály většinou poměr 4/3. Pokud je materriál moc velký, upravte procenta. **Poměr i procenta měňte pouze v následujícím řádku:**

    <div style="width:60%; aspect-ratio:5/4;">
 
Po změně 
[![Download file](https://img.shields.io/badge/download-prehravac.html-brightgreen)](https://raw.githubusercontent.com/uzivatel/repo/main/prehravac.html)

## Soubory ke stažení

- [![Download](https://img.shields.io/badge/Download-prehravac.html-blue?style=flat-square)](...)
- [![Download](https://img.shields.io/badge/Download-ruffle.js-blue?style=flat-square)](...)
