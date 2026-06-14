Závěrečný projekt: Databáze zaměstnanců
Zadání projektu:
Jako můj projekt jsem si vybral databázi zaměstnanců. Program umožňuje zaměstnancům firmy přidávat, odebírat a povyšovat jednotlivé zaměstnance. Zároveň je program umí vypsat, ukládat a načítat.

Model tříd:

![Model tříd](model_trid.png)


Struktura aplikace:
V mém programu mám jen jednu třídu Databáze.cs (viz obrázek 1).
Tato třída mi umožňuje přidávat objekty zaměstnanců do List<Databáze> databáze.

V Program.cs mám hlavní kód, který je rozdělen na metody pro jednodušší orientaci, např. PřidatZaznam, ZobrazitDatabázi, atd.

Popis práce se soubory
V projektu ukládám a načítám 2 soubory:

TXT soubor

ukládám do něj Dictionary<string, string> ucty

obsahuje uživatelská jména a hesla účtů

JSON soubor

ukládám do něj objekty zaměstnanců z listu databáze

Popis ovládání:
Po spuštění programu se uživateli zobrazí možnost přihlášení (pokud už má účet) nebo registrace.
Do programu se dá zaregistrovat pouze tehdy, pokud je uživatelské jméno zapsané v databázi.

Po přihlášení se zobrazí menu možností, které se ovládá pomocí čísel odpovídajících jednotlivým volbám.
Po výběru je uživatel přenesen do dané metody.

Databáze se uloží pouze tehdy, pokud se uživatel odhlásí pomocí možnosti Uložit a Odhlásit.
