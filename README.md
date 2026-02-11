# SPŠT Maturitní práce - Typst šablona

Toto je šablona pro tvorbu maturitní práce na Střední průmyslové škole Třebíč pomocí [Typst](https://typst.app/).

> [!WARN]
> Použití šablony je na vlastní nebezepečí. Negarantuji, že při použití vám nebudou strženy body za formátování a úpravy.

## Jak používat

Importujte si soubor `template.typ` do vašeho vlastního souboru `.typ` souboru a poté použijte funkci thesis. 
Příklad s default hodnotami:

```typ
#thesis(
  name: "Název maturitní práce",
  major: "Informační technologie",
  class: "ITB4",
  year: 2025,
  author: "Jméno Příjmení",
  abstract-cs: [
    Tvorba maturitní práce je jedním z velmi klíčových momentů při studiu. Kvalita zpracování její formální části je pak jedním z nejdůležitějších kritérií při jejím hodnocení. Cíl této práce je popsat jednotlivé kroky během tohoto procesu, doporučit postupy a vytvořit šablonu, která usnadní celý proces.
  ],
  abstract-en: [
    The creation of a graduation thesis is one of the most crucial moments during studies. The quality of the processing of its formal part is then one of the most important criteria in its evaluation. The aim of this work is to describe the individual steps during this process, recommend procedures and create a template that will facilitate the entire process.
  ],
  keywords-cs: [
    maturitní práce, šablona
  ],
  keywords-en: [
    graduation thesis, template
  ],
  acknowledgements: [
    Děkuji Mgr. Petru Novotnému za cenné připomínky a rady, které mi poskytl při vypracování maturitní práce.
  ],
  assignment: [
    Zadání maturitní práce je přílohou této práce.
  ],
  declaration: [
    Prohlašuji, že jsem tuto práci vypracoval/a samostatně a uvedl/a v ní všechny prameny, literaturu a ostatní zdroje, které jsem použil/a.
  ],
  date: "15. května 2024",
  body: [])

```

## Licence

Tento projekt je licencován pod [MIT licencí](LICENSE).

## Poděkování

Tato šablona využívá [modifikovanou šablonu pro citování dle normy ČSN ISO 690-2022](./iso690-2022.csl). Tato šablona používá licenci CC0 1.0 Universal. Původními autory jsou:
Marta Zizienová, Adam Zizien. Originální verze je dostupná online: https://github.com/zizienova/zoteroTUL2022