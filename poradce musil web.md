# CLAUDE.md – Osobní web Marek Musil

## O projektu

Osobní web finančního poradce Marka Musila na doméně **poradce-musil.cz**.
Cílem webu je budování osobního brandu a důvěryhodnosti – ne firemní prezentace firmy Financero, ale osobní profesionální profil autora.

## Autor

- **Jméno:** Marek Musil
- **Profese:** Finanční poradce
- **Firma:** Financero, s.r.o. (IČO: 08982171)
- **Email:** marek.musil@financero.cz
- **Telefon:** +420 732 187 153
- **LinkedIn:** linkedin.com/in/marekmusil
- **Facebook:** facebook.com/marek.musil.3
- **Profil Financero:** financero.cz/profil-poradce/marek-musil
- **Doména webu:** poradce-musil.cz
- **Osobní schůzky:** Brno
- **Online konzultace:** celá ČR
- **Členství:** Asociace finančních poradců ČR (AFP ČR)

---

## Pravidla pro texty (POVINNÁ)

1. **Nepoužívat slovo „nezávislý"** – je v rozporu s legislativou ČR pro finanční poradce. Nikdy, nikde, v žádném kontextu.
2. **Nepoužívat anglicismy** – místo „remote" psát „online" nebo „na dálku", místo „fee-based" psát „placené poradenství". Texty musí být srozumitelné pro běžného Čecha.
3. **Placené poradenství = upřednostňovaný model** – Marek upřednostňuje model, kde klient platí za poradenství, ne za uzavřené produkty. Nepoužívat slovo „výhradně" – model je upřednostňovaný, ne jediný.
4. **Osobní schůzky pouze Brno** – Marek není osobně dostupný po celé ČR. Online konzultace ano, po celé ČR.
5. **Osobní tón** – web mluví za Marka, ne za firmu. Přátelský, profesionální, bez žargonu.
6. **Kompaktnost** – stránka má být přehledná a kompaktní, ne roztáhlá. Méně je více.

---

## Klíčové principy webu

- **Placené poradenství** – klient platí za radu, ne za uzavřené smlouvy. Odměna je jasná a předem dohodnutá.
- **Multioborový přesah** – Marek dokáže konzultovat i přidružené otázky (právo, reality) a zapojuje tým specialistů.
- **Propojení perspektiv** – zkušenosti z práce s majetnějšími klienty přenáší k těm v akumulační fázi a naopak.
- **Tým odborníků** – na specifická témata má za sebou prověřené specialisty. Klient komunikuje s Markem, on koordinuje.

## Cíl webu

- Budování osobního brandu a důvěryhodnosti
- Prezentace služeb, ceníku a odbornosti
- Získávání kontaktů od potenciálních klientů
- Web má působit **osobně a profesionálně**, ne korporátně

---

## Obsah webu

### Sekce
1. **Hero** – titulní fotka (kancl.png), badge „Finanční poradce · Brno · osobně nebo online", headline o placeném poradenství, CTA tlačítka, 3 stat boxy
2. **Value bar** – 4 hodnoty: jasná odměna, bez tlaku na produkty, široký přesah, osobně i online
3. **O mně** – layout: levý sloupec (fotka balon.jpg + certifikace), pravý sloupec (bio, tagy, box Financero/AFP ČR). Levý sloupec je sticky.
4. **Tým odborníků** – 6 karet (grid 3×2): finanční a krizové poradenství, hypotéky a úvěry, investice, pojištění, právní služby, realitní služby
5. **Ceník služeb** – 6 služeb s cenami dle ODS souboru
6. **Kontakt** – telefon, email, osobní schůzky (Brno), online (celá ČR), 3 sociální sítě, formulář (Formspree)

### Ceník služeb
| Služba | Cena |
|---|---|
| Tvorba finančního plánu | 4 000 – 15 000 Kč |
| Tvorba finančního portfolia | 3 000 – 25 000 Kč |
| Servis úvěrových produktů | 3 000 – 10 000 Kč |
| Produktové srovnání | 3 000 – 10 000 Kč |
| Obecná konzultace | 900 Kč / hodina |
| Realitní služby | 1 500 Kč / hodina |

### Tým odborníků
- **Finanční a krizové poradenství** – stabilizace rozpočtu, cesta k finanční rovnováze
- **Hypotéky a úvěry** – srovnání nabídek, zpracování žádostí, financování
- **Investice** – správa portfolia, fondy, ETF, alternativní investice
- **Pojištění** – životní, majetkové, podnikatelské, revize smluv
- **Právní služby** – smlouvy, daně, dědictví, majetková práva
- **Realitní služby** – koupě, prodej, pronájem, propojení s financováním

### Certifikace (pod fotkou v levém sloupci sekce O mně)
- **EUCS** – ochrana práv klientů na finančním trhu (European Compensation Services)
- **Investiční poradce** – poradenství v oblasti investic
- **PFP** – osobní finanční plánování
- **Penze** – důchodové spoření a penzijní produkty
- **Pojištění** – životní i neživotní pojistné produkty
- **Úvěry** – spotřebitelské a hypoteční úvěry

### Tón komunikace
- Osobní, přátelský, ale profesionální
- Český jazyk, bez cizího žargonu a anglicismů
- Důraz na důvěru a odbornost
- Srozumitelnost pro běžného člověka

---

## Technické požadavky

- **Technologie:** čisté HTML + CSS + vanilla JS – žádné frameworky, žádné závislosti kromě Google Fonts
- **Typ webu:** landing page / digitální vizitka – single-page, vše v jednom `index.html`
- **Responzivní:** mobile-first, breakpointy 900px / 768px / 480px
- Rychlé načítání – minimální externí zdroje (pouze Google Fonts Nunito)
- Podpora českých znaků (UTF-8)
- Kontaktní formulář přes **Formspree** (bez vlastního backendu)
- Smooth scroll, fade-in animace (IntersectionObserver), staggered animace, hover efekty

## Design

### Vizuální styl
- Inspirace webem **financero.cz** – tmavý prémiový vzhled, čistý layout
- Fotografie autora jako klíčový prvek (2 fotky: kancl.png = hero, balon.jpg = O mně)
- Velká hero sekce s výrazným nadpisem a CTA
- **SVG wave oddělovače** mezi sekcemi (plynulé přechody)
- **Dekorativní prvky:** rohové zlaté čáry v hero, tečkovaný pattern, glow efekty
- **Gradient pozadí** sekcí (ne ploché barvy)
- **Kompaktní layout** – minimální zbytečné mezery, obsah hustě ale přehledně

### Typografie
- **Font: Nunito** (Google Fonts)
- Nadpisy: Nunito ExtraBold (800)
- Tělo textu: Nunito Regular (400) / SemiBold (600) / Bold (700)

### Barevná paleta
```
--bg-dark:      #1a1a2e   /* tmavé navy pozadí (primární) */
--bg-section:   #16213e   /* lehce světlejší sekce */
--bg-card:      #0f3460   /* karty a boxy */
--accent:       #c9a84c   /* zlatá – akcent, CTA tlačítka */
--accent-hover: #e2c16a   /* světlejší zlatá pro hover */
--text-light:   #ffffff   /* bílý text */
--text-muted:   #a0aec0   /* šedý text – popisky */
--border:       #2d3748   /* jemné bordery */
```

### Layout principy
- Mobile-first, responzivní
- Sekce na celou šířku s gradientním tmavým pozadím
- Bílý text na tmavém pozadí, zlatý akcent pro důležité prvky
- Zaoblené rohy karet (border-radius: 14px)
- Jemné stíny, hover animace, staggered fade-in
- Sticky levý sloupec v sekci O mně (fotka + certifikace)

---

## Co web NENÍ

- Není to firemní web Financero
- Není to e-shop ani složitá aplikace
- Není to blog (zatím)
- Nepoužívá slovo „nezávislý" (legislativa)
- Nepoužívá anglicismy

## Soubory a struktura projektu

```
/
├── index.html              # Celý web v jednom souboru (HTML + CSS + JS)
├── kancl.png               # Titulní fotka (hero sekce)
├── balon.jpg               # Sekundární fotka (sekce O mně, levý sloupec)
├── ceník.ods               # Zdrojový ceník služeb
├── odkazy.txt              # Odkazy na sociální sítě
├── *.pdf                   # Certifikáty (EUCS, PFP, Penze, Pojištění, Úvěry, Investiční poradce)
├── poradce musil web.md    # Tento soubor – dokumentace projektu
└── .claude/
    └── launch.json         # Konfigurace dev serveru
```

---

## Poznámky pro Claude (VŽDY dodržovat)

1. Vždy piš texty v češtině, srozumitelně pro běžného člověka
2. Zachovej osobní tón – web mluví za Marka, ne za firmu
3. **NIKDY nepoužívej slovo „nezávislý"** – rozpor s legislativou
4. **NIKDY nepoužívej anglicismy** (remote → online/na dálku)
5. Při generování kódu preferuj přehlednost a komentáře
6. Kontaktní formulář nesmí odesílat citlivá finanční data
7. Respektuj GDPR – souhlas se zpracováním osobních údajů u formuláře
8. Osobní schůzky pouze Brno, online konzultace celá ČR
9. Model placeného poradenství je „upřednostňovaný", ne „výhradní"
10. Dbej na kompaktnost – stránka nemá být zbytečně roztáhlá
11. Zachovej stávající vizuální styl (tmavé navy + zlatá), neměnit barevnou paletu
12. Při úpravách vždy aktualizovat i tento MD soubor
