# Js poznámky - školní projekt

Cílem projektu bylo vytvořit webovou aplikaci na vytváření poznámek s pomocí html, javascriptu a CSS.
Aplikace využívá local storage, takže i po obnovení stránky nepřijdeme o poznámky.  Poznámky můžeme i exportovat ve formátu JSON v okně nastavení. Tam také můžeme všechny poznámky odstranit. Pro následný import stačí soubor přetáhnout do okna aplikace.

Při vytváření nové poznámky můžeme vybrat jestli jí chceme jako úkol nebo ne. Poté  jí uložíme stisknutím klávesy enter. Po zaškrtnutí úkolu jako hotového se text poznámky škrtne. Když dvakrát po sobě klikneme na poznámku máme možnost změnit její obsah. Všechny tyto změny se ihned po provedení zapisují i do local storage. Poznámku odstraníme stisknutím křížku u poznámky. Po jejím smazání se přehraje zvuk smazání.

Na levé straně stránky jsou tři záložky pro přepínání zobrazení mezi všemi poznámkami, již hotovými a právě aktivními.

Pokud je stránka užší než 700px boční panel zmizí a objeví se ikonka menu. Po jejím stisknutí se panel opět objeví.
