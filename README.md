# Power BI Projekt: Dostupnost potravin vs. mzdy

## O projektu

Tato část projektu navazuje na SQL analýzu a zaměřuje se na **vizualizaci dat** pomocí nástroje Power BI. Pomocí interaktivních dashboardů prezentuje vývoj **průměrných mezd**, **cen základních potravin** a jejich **cenovou dostupnost** v čase.

Hlavním cílem j ukázat:
- rozdíly v mzdách napříč **kraji a odvětvími**,
- vývoj cen vybraných potravin v jednotlivých letech,
- jak se mění **kupní síla obyvatel** – kolik jednotek potravin si může průměrný občan dovolit koupit ze své mzdy.

## Obsah reportu

Projekt je rozdělen do několika stránek, každá reprezentuje jednu oblast:

1. **Vývoj mezd podle odvětvíí** – srovnání průměrných mezd napříč sektory od roku 2000.
2. **Vývoj cen potravin** – analýza cen vybraných položek spotřebního koše.
3. **Vývoj mezd podle krajů** – regionílní rozdíly v odměňování.
4. **Kupní síla** – počet jednotek potravin, které si lze koupit za průměrnou mzdu v daném roce.
5. **Navigace & interaktivita** – záložky, slicery a přehledné ovládání.

## Použité datové zdroje

- **czechia_payroll**
- **dczechia_payroll_industry_branch**
- **czechia_region**
- **czechia_price_category**
- **czechia_price**
- **wages_by_region** podrobné mzdy dle kraje, pohlaví a kvantilů (staženo z  Portálu otevřených dat ČR)

## Použité Power BI prvky

- Intersktivní **slicery** (filtry) pro rok, kraj, pohlaví, produkt apod.
- **Záložky a tlačítka** pro navigaci mezi stránkami.
- Vlastní **measures** a výpočty (např. *Jednotek_na_mzdu*).
- Propojení více tabulek přes Power Query a datový model.
- Vizuály: sloupcový graf, koláčový graf, mapa, slicery, kombinované vizualizace.

## Výzkumné otázky (viz SQL část)

Viz [SQL README](../SQL/README.md) – Power BI část přináší odpovědi na výzkumné otázky formou vizualizací a interaktivních přehledů.

## Autor

Ján Gondáš – vizualizace vytvořena v rámci kurzu Datová akademieod Engeto.

