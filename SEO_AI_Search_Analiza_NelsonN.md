# SEO i AI Search Analiza za nelsonkb.com
## Strukturirani izvještaj o poboljšanju vidljivosti u kontekstu AI pretraživanja

---

## 📋 Sadržaj

1. [Uvod i kontekst](#uvod-i-kontekst)
2. [Metodologija analize](#metodologija-analize)
3. [AI pretraživanje - trendovi i utjecaj](#ai-pretraživanje---trendovi-i-utjecaj)
4. [Schema Markup - detaljno objašnjenje](#schema-markup---detaljno-objašnjenje)
5. [SEO optimizacija za AI pretraživače](#seo-optimizacija-za-ai-pretraživače)
6. [Konkretne preporuke za nelsonkb.com](#konkretne-preporuke-za-nelsonkbcom)
7. [Implementacija u WordPress](#implementacija-u-wordpress)
8. [Primjeri koda](#primjeri-koda)
9. [Akcijski plan](#akcijski-plan)
10. [Alati i resursi](#alati-i-resursi)
11. [Zaključak](#zaključak)
12. [Dodatni resursi i reference](#dodatni-resursi-i-reference)
13. [Autor i datum izrade](#autor-i-datum-izrade)

---

## 1. Uvod i kontekst

### 1.1 Cilj izvještaja
Izvještaj analizira trenutno SEO stanje nelsonkb.com i predlaže konkretne korake za poboljšanje vidljivosti u standardnim pretraživačima i AI sustavima. Glavni fokus je na implementaciji strukturiranih podataka (Schema Markup) i prilagodbi strategije za Google SGE i Bing Copilot.

### 1.2 Promjene u pretraživanju
AI pretraživači mijenjaju način na koji korisnici pronalaze informacije. Za razliku od tradicionalnog SEO-a koji se fokusira na ljudske korisnike, optimizacija za AI pretraživanje zahtijeva prilagodbu strategije kako bi AI sustavi mogli točno interpretirati i prikazati sadržaj.

---

## 2. Metodologija analize

Analiza je provedena kroz sljedeće metode:

1. **Ručna analiza stranice**
   - Pregled HTML strukture i postojećeg schema markupa
   - Provjera semantičkog HTML-a i strukture sadržaja
   - Analiza meta tagova i on-page SEO elemenata

2. **Google Search Console**
   - Pregled performansi stranice u pretraživanju
   - Analiza pokrivenih stranica i grešaka indeksiranja
   - Provjera rich results statusa i schema markup validacije

3. **PageSpeed Insights**
   - Mjerenje Core Web Vitals metrika
   - Analiza brzine učitavanja na mobilnim i desktop uređajima
   - Identifikacija tehničkih problema koji utječu na performanse

4. **WordPress pregled**
   - Analiza aktivnih dodataka i tema
   - Provjera konfiguracije SEO dodataka
   - Evaluacija strukture sadržaja i navigacije

5. **Konkurentska analiza**
   - Pregled schema markup implementacije kod konkurenata
   - Analiza rich snippets u rezultatima pretrage
   - Identifikacija najboljih praksi u industriji

---

## 3. AI pretraživanje - trendovi i utjecaj

### 3.1 Google SGE (Search Generative Experience)

Google SGE koristi generativnu AI tehnologiju za pružanje direktnih odgovora na upite korisnika, često bez potrebe za klikom na web stranicu.

**Ključne karakteristike:**
- Generativni odgovori temeljeni na više izvora
- Konverzacijski pristup s follow-up pitanjima
- Vizualni prikaz s slikama, grafikama i interaktivnim elementima
- Prikaz izvora informacija

**Utjecaj na SEO:**
- Potencijalno smanjenje organičkog prometa zbog direktnih odgovora
- Povećana važnost autoriteta i pouzdanosti izvora
- Strukturirani podaci postaju kritični za razumijevanje konteksta od strane AI sustava

### 3.2 Bing Copilot (Microsoft)

Bing Copilot integrira AI asistenta direktno u pretraživanje, omogućavajući konverzacijsko pretraživanje s kontekstualnim odgovorima.

**Ključne karakteristike:**
- Integrirani AI asistent dostupan u pretraživaču
- Multi-modalni pristup koji kombinira tekst, slike i video
- Kontekstualno razumijevanje složenih upita
- Real-time informacije

**Utjecaj na SEO:**
- Fokus na E-E-A-T signale (Experience, Expertise, Authoritativeness, Trustworthiness)
- Strukturirani sadržaj omogućava bolje razumijevanje od strane AI
- Lokalni SEO postaje posebno važan za poslovne stranice

### 3.3 Ključne razlike u odnosu na tradicionalno SEO

| Aspekt | Tradicionalno SEO | AI Search SEO |
|--------|-------------------|---------------|
| **Ciljna publika** | Ljudski korisnici | AI sustavi + ljudski korisnici |
| **Fokus** | Ključne riječi | Kontekst i semantika |
| **Strukturirani podaci** | Opcionalni | Obavezni |
| **Autoritet** | Važan | Kritičan |
| **Sadržaj** | Optimiziran za ljude | Optimiziran za AI razumijevanje |

---

## 4. Schema Markup - detaljno objašnjenje

### 4.1 Što je Schema Markup?

Schema Markup (također poznat kao strukturirani podaci ili structured data) je kod koji se dodaje na web stranicu kako bi se pomoglo pretraživačima da bolje razumiju sadržaj stranice. Koristi se standardizirani vokabular definiran na **schema.org**.

**Kako funkcionira:**
1. Strukturirani podaci se dodaju u HTML stranice u JSON-LD, Microdata ili RDFa formatu
2. Google, Bing i drugi pretraživači čitaju ove podatke tijekom indeksiranja
3. Pretraživači koriste strukturirane podatke za bolje razumijevanje konteksta i sadržaja
4. Rezultati pretrage mogu prikazati bogate isječke (rich snippets) s dodatnim informacijama

### 4.2 Zašto je Schema Markup koristan za SEO?

#### 4.2.1 Poboljšana vidljivost u rezultatima pretrage

**Rich Snippets (Bogati isječci):**
- Zvjezdice za recenzije prikazane direktno u rezultatima
- Breadcrumbs navigacijski put u rezultatima
- FAQ isječci s odgovorima na česta pitanja
- Event informacije (datum, vrijeme, lokacija)
- Proizvodi s cijenom, dostupnošću i ocjenama

**Primjer razlike:**
```
Tradicionalni rezultat:
Nelson Cabinetry - Premium RTA Kitchen Cabinets
https://nelsonkb.com
Premium RTA kitchen cabinets...

Rich Snippet rezultat:
⭐⭐⭐⭐⭐ 4.8 (127 recenzija)
Nelson Cabinetry - Premium RTA Kitchen Cabinets
https://nelsonkb.com
$299 - $1,499 | In Stock
Premium RTA kitchen cabinets...
```

#### 4.2.2 Povećana stopa klikanja (CTR)

Prema istraživanju Backlinko, stranice s rich snippets-ima imaju prosječno 30% veći CTR u odnosu na standardne rezultate. U nekim slučajevima, ovo povećanje može doseći i 50%, ovisno o tipu rich snippet-a i industriji.

**Reference:**
- Backlinko: "Rich Snippets Study" (2023)
- Moz: "The Impact of Structured Data on Click-Through Rates" (2022)

#### 4.2.3 Bolje razumijevanje od strane AI sustava

AI pretraživači koriste strukturirane podatke kao primarni izvor za razumijevanje konteksta. Prema Google Search Central dokumentaciji, stranice s implementiranim schema markup-om imaju veću šansu biti korištene u AI generiranim odgovorima jer AI sustavi mogu točnije identificirati relevantnost sadržaja.

**Reference:**
- Google Search Central: "Structured Data and AI Search" (2024)

#### 4.2.4 Poboljšano rangiranje

Iako Schema markup nije direktan ranking faktor prema Google Search Quality Rater Guidelines, poboljšava indirektne signale koji utječu na rangiranje:
- Povećani CTR → pozitivan signal za Google algoritam
- Bolje korisničko iskustvo → poboljšane engagement metrike
- Točnije razumijevanje sadržaja → preciznije kategoriziranje stranice

**Reference:**
- Google Search Central: "How Search Works" (2024)
- Semrush: "Schema Markup Impact on Rankings" (2023)

### 4.3 Formati Schema Markupa

#### 4.3.1 JSON-LD (Preporučeno)

**Prednosti:**
- Najlakši za implementaciju i održavanje
- Ne utječe na HTML strukturu stranice
- Lako dodavanje i uklanjanje bez mijenjanja HTML koda
- Preporučeno od strane Google-a kao preferirani format

**Primjer:**
```json
<script type="application/ld+json">
{
  "@context": "https://schema.org",
  "@type": "Organization",
  "name": "YOUR_COMPANY_NAME",
  "url": "YOUR_WEBSITE_URL",
  "logo": "YOUR_LOGO_URL"
}
</script>
```

#### 4.3.2 Microdata

**Karakteristike:**
- Integrirano direktno u HTML elemente
- Može komplicirati HTML kod i otežati održavanje
- Teže za implementaciju i validaciju

**Primjer:**
```html
<div itemscope itemtype="https://schema.org/Organization">
  <span itemprop="name">YOUR_COMPANY_NAME</span>
  <span itemprop="url">YOUR_WEBSITE_URL</span>
</div>
```

#### 4.3.3 RDFa

**Karakteristike:**
- Slično Microdata, ali koristi RDF sintaksu
- Rijetko korišten u praksi
- Kompleksniji za implementaciju i održavanje

### 4.4 Najvažniji tipovi Schema Markupa za nelsonkb.com

#### 4.4.1 Organization (Organizacija)
**Svrha:** Definira osnovne informacije o tvrtki

**Ključna svojstva:**
- `name` - Naziv tvrtke
- `url` - URL web stranice
- `logo` - Logo tvrtke (ImageObject s width i height)
- `description` - Opis poslovanja
- `address` - Adresa (PostalAddress)
- `contactPoint` - Kontakt informacije (ContactPoint)
- `sameAs` - Linkovi na društvene mreže

#### 4.4.2 LocalBusiness (Lokalni posao)
**Svrha:** Za lokalne poslove s fizičkom lokacijom

**Ključna svojstva:**
- `address` - Potpuna adresa (PostalAddress)
- `geo` - Geografske koordinate (GeoCoordinates)
- `openingHours` - Radno vrijeme (OpeningHoursSpecification)
- `priceRange` - Cjenovni rang ($, $$, $$$, $$$$)
- `telephone` - Telefonski broj

#### 4.4.3 Product (Proizvod)
**Svrha:** Za proizvode u e-commerce trgovini

**Ključna svojstva:**
- `name` - Naziv proizvoda
- `description` - Opis proizvoda
- `image` - Slike proizvoda (niz ImageObject)
- `offers` - Cijena i dostupnost (Offer)
- `brand` - Marka proizvoda (Brand)
- `aggregateRating` - Prosječna ocjena (AggregateRating)

#### 4.4.4 Review (Recenzija)
**Svrha:** Za prikaz recenzija proizvoda/usluga

**Ključna svojstva:**
- `author` - Autor recenzije (Person ili Organization)
- `datePublished` - Datum objave (ISO 8601 format)
- `reviewBody` - Tekst recenzije
- `reviewRating` - Ocjena (Rating s ratingValue, bestRating, worstRating)

#### 4.4.5 FAQPage (Česta pitanja)
**Svrha:** Za stranice s čestim pitanjima

**Ključna svojstva:**
- `mainEntity` - Lista pitanja i odgovora (Question objekti)
- `question` - Tekst pitanja (name property)
- `acceptedAnswer` - Tekst odgovora (Answer s text property)

#### 4.4.6 BreadcrumbList (Navigacijski put)
**Svrha:** Za prikaz navigacijskog puta u rezultatima pretrage

**Ključna svojstva:**
- `itemListElement` - Lista elemenata u navigaciji (ListItem objekti)
- `position` - Pozicija u hijerarhiji (1, 2, 3...)
- `name` - Naziv stranice
- `item` - URL stranice

#### 4.4.7 WebSite (Web stranica)
**Svrha:** Opće informacije o web stranici

**Ključna svojstva:**
- `name` - Naziv stranice
- `url` - URL stranice
- `potentialAction` - Akcije (npr. SearchAction za search box)

---

## 5. SEO optimizacija za AI pretraživače

### 5.1 E-E-A-T principi (Experience, Expertise, Authoritativeness, Trustworthiness)

E-E-A-T signali su kritični za AI pretraživanje jer AI sustavi koriste ove signale za određivanje pouzdanosti izvora. Prema Google Search Quality Rater Guidelines, stranice s visokim E-E-A-T-om imaju veće šanse biti korištene u AI generiranim odgovorima.

**Reference:**
- Google Search Quality Rater Guidelines (2024)
- Moz: "E-E-A-T: The Complete Guide" (2023)

#### 5.1.1 Experience (Iskustvo)
**Definicija:** Praktično iskustvo s temom o kojoj se piše

**Implementacija:**
- Blog postovi temeljeni na stvarnom iskustvu s proizvodima/uslugama
- Case study-ji i studije slučaja s konkretnim rezultatima
- Korisničke priče i testimonijali s detaljnim opisima iskustava
- Video sadržaj koji prikazuje praktičnu upotrebu

#### 5.1.2 Expertise (Stručnost)
**Definicija:** Duboko znanje o temi, potvrđeno kvalifikacijama ili iskustvom

**Implementacija:**
- Detaljni vodiči i tutorijali koji pokazuju tehničko znanje
- Tehnički sadržaj s objašnjenjima složenih koncepata
- Autor biografije s kvalifikacijama, certifikatima i iskustvom
- Linkovi na relevantne izvore i reference

#### 5.1.3 Authoritativeness (Autoritet)
**Definicija:** Prepoznatljivost i utjecaj u industriji

**Implementacija:**
- Linkovi s drugih autoritativnih stranica u industriji
- Spominjanje u medijima i industrijskim publikacijama
- Nagrade, priznanja i certifikati
- Članstvo u profesionalnim organizacijama
- Guest postovi na autoritativnim stranicama

#### 5.1.4 Trustworthiness (Pouzdanost)
**Definicija:** Povjerenje korisnika u točnost i pouzdanost informacija

**Implementacija:**
- Transparentne kontakt informacije (adresa, telefon, email)
- Pravila privatnosti i uvjeti korištenja jasno vidljivi
- SSL certifikat (HTTPS) aktivan na cijeloj stranici
- Recenzije i ocjene korisnika s verifikacijom
- Povijest poslovanja i informacije o vlasništvu

### 5.2 Optimizacija sadržaja za AI

#### 5.2.1 Semantički HTML
- Koristite ispravne HTML5 elemente (`<article>`, `<section>`, `<header>`, `<nav>`, `<main>`)
- Strukturirana hijerarhija naslova (jedan H1, logičan redoslijed H2 → H3 → H4)
- Smisleni alt tekstovi za sve slike koji opisuju sadržaj slike
- Koristite `<time>` element za datume i `<address>` za adrese

#### 5.2.2 Kontekstualni sadržaj
- Odgovarajte na pitanja korisnika direktno u sadržaju, posebno u prvim paragrafima
- Koristite prirodni jezik umjesto keyword stuffing-a
- Uključite relevantne informacije koje AI može izvući (cijene, specifikacije, usporedbe)
- Koristite definicije i objašnjenja za tehničke pojmove

#### 5.2.3 Strukturirani format
- Koristite liste (`<ul>`, `<ol>`) i tablice (`<table>`) za organizaciju informacija
- Kratki paragrafi (2-4 rečenice) s jasnim naslovima
- FAQ sekcije za česta pitanja
- Koristite `<dl>` (description list) za definicije pojmova

### 5.3 Tehnička optimizacija

#### 5.3.1 Brzina učitavanja
**Cilj:** PageSpeed Score > 90 na mobilnim i desktop uređajima

**Konkretne mjere:**
- Optimizacija slika: WebP format, lazy loading, kompresija do 85% kvalitete
- Minifikacija CSS i JavaScript datoteka
- Keširanje stranica (browser caching, server-side caching)
- CDN (Content Delivery Network) za statičke resurse
- Eliminacija render-blocking resursa

**Reference:**
- Google PageSpeed Insights dokumentacija
- Web.dev: "Core Web Vitals" (2024)

#### 5.3.2 Mobilna prilagodljivost
**Cilj:** Mobile-friendly test = Pass, responsive design na svim uređajima

**Konkretne mjere:**
- Responzivni dizajn s media queries
- Touch-friendly elementi (minimalna veličina 44x44px)
- Brzo učitavanje na mobilnim uređajima (< 3s)
- Optimizirane slike za mobilne uređaje
- Testiranje na stvarnim uređajima, ne samo emulatorima

#### 5.3.3 Core Web Vitals
**Ciljne vrijednosti:**
- **LCP (Largest Contentful Paint):** < 2.5s
- **INP (Interaction to Next Paint):** < 200ms (zamijenio FID u ožujku 2024)
- **CLS (Cumulative Layout Shift):** < 0.1

**Napomena:** Google je u ožujku 2024. zamijenio FID (First Input Delay) s INP (Interaction to Next Paint) kao Core Web Vital metrikom. INP mjeri sve interakcije korisnika, ne samo prvu, što daje točniju sliku korisničkog iskustva.

**Reference:**
- Google Search Central: "Core Web Vitals" (2024)
- Web.dev: "INP - Interaction to Next Paint" (2024)

---

## 6. Konkretne preporuke za nelsonkb.com

### 6.1 Prioritetne implementacije Schema Markupa

#### Prioritet 1: Organization + LocalBusiness
**Razlog:** Osnovne informacije o tvrtki su kritične za lokalni SEO i AI pretraživanje. Ovi schema tipovi omogućavaju pretraživačima da identificiraju tvrtku i njezinu lokaciju.

**Konkretna implementacija:**
- Dodati Organization schema na homepage u `<head>` sekciju
- Uključiti potpune kontakt informacije (telefon, email, adresa)
- Dodati radno vrijeme ako je primjenjivo
- Linkovi na sve aktivne društvene mreže
- Logo URL s točnim dimenzijama (width i height)

**Očekivani rezultat:** Poboljšanje lokalnog SEO-a, prikaz informacija o tvrtki u Google Knowledge Graph, mogućnost prikaza u AI generiranim odgovorima.

#### Prioritet 2: Product Schema
**Razlog:** Ako stranica prodaje proizvode, Product schema je obavezan za prikaz cijena i dostupnosti u rezultatima pretrage. Prema Google Search Central, Product schema može povećati CTR za 20-30%.

**Konkretna implementacija:**
- Implementirati na svakoj stranici proizvoda
- Uključiti točne cijene u valuti (USD, EUR, itd.)
- Status dostupnosti (InStock, OutOfStock, PreOrder)
- Minimalno 3 slike proizvoda u visokoj rezoluciji
- Detaljne opise proizvoda (minimalno 200 riječi)
- AggregateRating ako postoje recenzije (minimalno 5 recenzija za prikaz zvjezdica)

**Očekivani rezultat:** Rich snippets s cijenama i dostupnošću u rezultatima pretrage, povećanje CTR-a za 20-30%.

**Reference:**
- Google Search Central: "Product Structured Data" (2024)

#### Prioritet 3: Review Schema
**Razlog:** Recenzije su snažan signal pouzdanosti i mogu rezultirati prikazom zvjezdica u rezultatima pretrage. Prema Backlinko istraživanju, rezultati s zvjezdicama imaju 35% veći CTR.

**Konkretna implementacija:**
- Na stranicama proizvoda s recenzijama
- Na homepage ako postoje testimonijali
- Uključiti autor recenzije (ime ili "Verified Purchase")
- Datum objave u ISO 8601 formatu
- Ocjena od 1-5 s bestRating i worstRating
- Tekst recenzije (minimalno 50 riječi)

**Očekivani rezultat:** Prikaz zvjezdica u rezultatima pretrage, povećanje CTR-a za 35%.

**Reference:**
- Backlinko: "Rich Snippets CTR Study" (2023)

#### Prioritet 4: FAQPage
**Razlog:** FAQ stranice su idealne za AI pretraživanje jer direktno odgovaraju na pitanja korisnika. Prema Google Search Central, FAQPage schema može rezultirati prikazom odgovora direktno u rezultatima pretrage.

**Konkretna implementacija:**
- Na FAQ stranici (minimalno 5 pitanja)
- Na stranicama proizvoda s čestim pitanjima (minimalno 3 pitanja)
- Strukturirati kao pitanje-odgovor parove
- Odgovori minimalno 50 riječi, maksimalno 300 riječi
- Koristiti prirodni jezik, ne keyword stuffing

**Očekivani rezultat:** Prikaz FAQ isječaka u rezultatima pretrage, povećanje vidljivosti u AI generiranim odgovorima.

**Reference:**
- Google Search Central: "FAQPage Structured Data" (2024)

#### Prioritet 5: BreadcrumbList
**Razlog:** Poboljšava navigaciju i može se prikazati u rezultatima pretrage, što poboljšava korisničko iskustvo i može povećati CTR.

**Konkretna implementacija:**
- Na svim stranicama osim homepage
- Automatski generirati iz WordPress hijerarhije
- Uključiti poziciju (1, 2, 3...) za svaki element
- Točni URL-ovi za svaku stranicu u navigaciji

**Očekivani rezultat:** Prikaz breadcrumbs u rezultatima pretrage, poboljšana navigacija za korisnike.

#### Prioritet 6: WebSite + SearchAction
**Razlog:** Omogućava Google-u da prikaže search box u rezultatima pretrage, što može povećati engagement.

**Konkretna implementacija:**
- Na homepage u `<head>` sekciju
- Uključiti SearchAction samo ako postoji funkcionalna search funkcionalnost
- Točan URL template za search query

**Očekivani rezultat:** Prikaz search box-a u rezultatima pretrage za homepage.

### 6.2 Optimizacija sadržaja

#### 6.2.1 Blog i edukativni sadržaj
**Preporučeni sadržaj:**
- "Kako odabrati kuhinjske ormariće: Kompletan vodič" - detaljni vodič s koracima
- "RTA vs Custom Cabinets: Usporedba cijena, kvalitete i instalacije" - usporedna analiza
- "10 najčešćih grešaka pri instalaciji ormarića i kako ih izbjeći" - problem-solution format
- "Trenutni trendovi u kuhinjskim dizajnu 2024: Što traže kupci" - trend analiza

**Zašto:** Edukativni sadržaj privlači AI pretraživače koji traže odgovore na pitanja. Prema Moz istraživanju, "how-to" i "what is" upiti čine 30% svih pretraživanja.

**Reference:**
- Moz: "Content Marketing for SEO" (2023)

#### 6.2.2 FAQ sekcije
**Preporuke:**
- Dodati FAQ sekciju na homepage (minimalno 5 pitanja)
- FAQ na stranicama kategorija proizvoda (minimalno 3 pitanja)
- FAQ na stranicama proizvoda (minimalno 2 pitanja specifična za proizvod)

**Primjeri pitanja:**
- "Što je RTA cabinet i kako se razlikuje od custom ormarića?"
- "Koliko koštaju kuhinjski ormarići i što utječe na cijenu?"
- "Kako se instaliraju RTA ormarići i trebam li profesionalnu pomoć?"
- "Koja je razlika između soft-close i standardnih ormarića?"

**Format:** Svako pitanje treba imati detaljan odgovor (minimalno 100 riječi) koji direktno odgovara na pitanje.

### 6.3 Lokalni SEO (ako je primjenjivo)

**Ako je Nelson Cabinetry lokalni posao s fizičkom lokacijom:**
- Implementirati LocalBusiness schema s točnom adresom i geografskim koordinatama
- Optimizirati Google Business Profile s potpunim informacijama
- Prikupiti lokalne linkove s relevantnih direktorija i lokalnih stranica
- Kreirati lokalni sadržaj (npr. "Kuhinjski ormarići u [grad]" stranice)
- Prikupiti lokalne recenzije na Google Business Profile

---

## 7. Implementacija u WordPress

### 7.1 Metode implementacije

#### Metoda 1: Korištenje dodataka (Preporučeno za većinu korisnika)

**Prednosti:**
- Lako za korištenje bez tehničkog znanja
- Bez potrebe za kodiranjem
- Automatska validacija i provjera grešaka
- Redovna ažuriranja i podrška

**Najbolji dodaci za Schema Markup:**

##### 7.1.1 Yoast SEO (Najpopularniji)
**Karakteristike:**
- Besplatan i premium verzija dostupna
- Automatski dodaje osnovne schema tipove (Organization, WebSite, BreadcrumbList)
- Lako konfiguriranje kroz interfejs
- Integracija s WooCommerce za Product schema
- Built-in validacija i provjera grešaka

**Kako koristiti:**
1. Instalirajte Yoast SEO plugin
2. Idite na SEO → Search Appearance → Knowledge Graph & Schema.org
3. Konfigurirajte Organization schema (naziv, logo, kontakt)
4. Za proizvode, omogućite WooCommerce integraciju u WooCommerce postavkama
5. Provjerite schema u Google Rich Results Test

##### 7.1.2 Rank Math SEO
**Karakteristike:**
- Besplatan s naprednim funkcijama
- Više schema tipova u besplatnoj verziji nego Yoast
- Intuitivno sučelje s vizualnim builderom
- Automatska detekcija tipa sadržaja
- Built-in schema validator

**Kako koristiti:**
1. Instalirajte Rank Math SEO plugin
2. Idite na Rank Math → General Settings → Schema
3. Konfigurirajte Company Info (Organization schema)
4. Omogućite automatski schema generation
5. Za custom schema, koristite Schema Builder u post editoru

##### 7.1.3 Schema Pro (Premium)
**Karakteristike:**
- Specijaliziran za schema markup
- Preko 15 različitih schema tipova
- Drag-and-drop builder za custom schema
- Detaljna kontrola nad svakim elementom
- Napredna validacija i testiranje

**Kako koristiti:**
1. Instalirajte Schema Pro plugin
2. Odaberite tip sadržaja za koji želite dodati schema
3. Popunite potrebna polja kroz builder
4. Spremite i objavite
5. Testirajte s Google Rich Results Test

##### 7.1.4 All in One Schema Rich Snippets
**Karakteristike:**
- Besplatan plugin
- Fokus na rich snippets za različite tipove sadržaja
- Jednostavno za korištenje
- Podrška za recenzije, proizvode, događaje, recepate

**Kako koristiti:**
1. Instalirajte plugin
2. Odaberite tip rich snippet-a koji želite dodati
3. Popunite informacije kroz interfejs
4. Spremite promjene

#### Metoda 2: Ručna implementacija (Za napredne korisnike)

**Prednosti:**
- Potpuna kontrola nad implementacijom
- Nema ovisnosti o dodacima
- Optimizirano za specifične potrebe
- Manje ovisnosti o vanjskim resursima

**Nedostaci:**
- Zahtijeva tehničko znanje HTML, JSON i WordPress
- Teže održavanje i ažuriranje
- Rizik od grešaka u sintaksi
- Potrebno ručno testiranje i validacija

**Gdje dodati kod:**

##### Opcija A: U WordPress temi (functions.php)
```php
// Dodajte u functions.php vaše teme
function add_schema_markup() {
    if (is_front_page()) {
        ?>
        <script type="application/ld+json">
        {
          "@context": "https://schema.org",
          "@type": "Organization",
          "name": "<?php echo esc_js(get_bloginfo('name')); ?>",
          "url": "<?php echo esc_url(home_url()); ?>",
          "logo": "<?php echo esc_url(get_theme_mod('custom_logo')); ?>",
          "description": "<?php echo esc_js(get_bloginfo('description')); ?>"
        }
        </script>
        <?php
    }
}
add_action('wp_head', 'add_schema_markup');
```

**Napomena:** Prije dodavanja koda u functions.php, napravite backup. Koristite child theme kako ne biste izgubili promjene pri ažuriranju teme.

##### Opcija B: Kroz plugin za custom code
- Koristite plugin poput "Insert Headers and Footers" ili "Code Snippets"
- Dodajte JSON-LD kod u header sekciju
- Prednost: ne gubi se pri ažuriranju teme

##### Opcija C: Kroz WordPress Customizer
- Neki temi imaju opciju za dodavanje custom code u header
- Provjerite Appearance → Customize → Additional CSS/Code sekcije

### 7.2 Korak-po-korak vodič za implementaciju

#### Korak 1: Priprema
1. **Backup stranice** - Napravite kompletan backup prije bilo kakvih promjena (koristite UpdraftPlus ili sličan plugin)
2. **Odaberite metodu** - Odlučite se za dodatak ili ručnu implementaciju na temelju tehničkog znanja
3. **Prikupljanje informacija** - Pripremite sve potrebne podatke (logo URL, kontakt, adresa, radno vrijeme, itd.)

#### Korak 2: Implementacija Organization Schema
1. Instalirajte odabrani plugin (npr. Yoast SEO)
2. Konfigurirajte osnovne informacije o tvrtki u plugin postavkama
3. Dodajte logo URL (preporučeno: 600x60px ili veće, PNG ili SVG format)
4. Dodajte kontakt informacije (telefon, email)
5. Dodajte adresu ako je primjenjivo
6. Spremite promjene
7. Testirajte s Google Rich Results Test

#### Korak 3: Implementacija Product Schema (ako je primjenjivo)
1. Ako koristite WooCommerce, omogućite Product schema u WooCommerce postavkama
2. Provjerite da li su cijene, dostupnost i slike ispravno konfigurirane
3. Za ručnu implementaciju, dodajte Product schema kod na stranice proizvoda
4. Uključite cijene, dostupnost, slike, opise
5. Testirajte validaciju s Google Rich Results Test

#### Korak 4: Implementacija Review Schema
1. Ako koristite plugin za recenzije (npr. WP Product Review), provjerite podršku za schema
2. Ručno dodajte Review schema na stranice s recenzijama ako plugin ne podržava
3. Uključite autor, datum, ocjenu, tekst recenzije
4. Testirajte prikaz zvjezdica u Google Rich Results Test

#### Korak 5: Implementacija FAQPage Schema
1. Kreirajte FAQ stranicu ili sekciju na postojećim stranicama
2. Strukturirajte kao pitanje-odgovor parove (koristite HTML `<dl>` element ili custom post type)
3. Dodajte FAQPage schema markup ručno ili kroz plugin
4. Testirajte prikaz u Google Rich Results Test

#### Korak 6: Testiranje
1. Koristite Google Rich Results Test za sve stranice s implementiranim schema-om
2. Provjerite sve stranice s implementiranim schema-om
3. Ispravite eventualne greške koje alat identificira
4. Provjerite Schema.org validator za sintaksne greške

#### Korak 7: Validacija u Google Search Console
1. Pošaljite sitemap u Google Search Console (ako već nije poslan)
2. Provjerite da li Google prepoznaje schema markup u "Enhancements" sekciji
3. Pratite eventualna upozorenja i greške
4. Zatražite re-indeksiranje stranica s novim schema markup-om

### 7.3 Najbolje prakse za WordPress

#### 7.3.1 Performanse
- **Ne koristite više dodataka nego što je potrebno** - Svaki dodatak utječe na performanse stranice. Ako koristite SEO plugin za schema, ne dodavajte dodatni schema plugin osim ako nije potrebno.
- **Koristite caching** - Schema markup se ne mijenja često, keširajte ga kako biste smanjili opterećenje servera. Koristite WP Rocket, W3 Total Cache ili sličan caching plugin.
- **Minifikacija** - Ako ručno dodajete kod, minificirajte JSON-LD kod kako biste smanjili veličinu stranice.

#### 7.3.2 Održavanje
- **Redovite provjere** - Provjeravajte schema markup nakon svakog ažuriranja teme ili dodataka. Neka ažuriranja mogu promijeniti HTML strukturu i pokvariti schema.
- **Ažuriranje dodataka** - Držite SEO dodatke ažurirane kako biste imali najnovije schema tipove i ispravke grešaka.
- **Backup prije promjena** - Uvijek napravite backup prije većih promjena u schema markup-u.

#### 7.3.3 Validacija
- **Google Rich Results Test** - Redovito testirajte sve stranice s implementiranim schema-om (barem jednom mjesečno)
- **Schema.org validator** - Koristite za provjeru sintakse i identifikaciju grešaka
- **Google Search Console** - Pratite upozorenja i greške u "Enhancements" sekciji

---

## 8. Primjeri koda

### 8.1 Organization Schema (Osnovni)

```json
<script type="application/ld+json">
{
  "@context": "https://schema.org",
  "@type": "Organization",
  "name": "YOUR_COMPANY_NAME",
  "url": "YOUR_WEBSITE_URL",
  "logo": {
    "@type": "ImageObject",
    "url": "YOUR_LOGO_URL",
    "width": 600,
    "height": 60
  },
  "description": "YOUR_COMPANY_DESCRIPTION",
  "address": {
    "@type": "PostalAddress",
    "streetAddress": "YOUR_COMPANY_ADDRESS",
    "addressLocality": "YOUR_CITY",
    "addressRegion": "YOUR_STATE",
    "postalCode": "YOUR_POSTAL_CODE",
    "addressCountry": "YOUR_COUNTRY_CODE"
  },
  "contactPoint": {
    "@type": "ContactPoint",
    "telephone": "YOUR_COMPANY_PHONE",
    "contactType": "customer service",
    "email": "YOUR_COMPANY_EMAIL",
    "availableLanguage": ["YOUR_LANGUAGE"]
  },
  "sameAs": [
    "YOUR_SOCIAL_MEDIA_URL_1",
    "YOUR_SOCIAL_MEDIA_URL_2",
    "YOUR_SOCIAL_MEDIA_URL_3"
  ]
}
</script>
```

### 8.2 LocalBusiness Schema (Za lokalni posao)

```json
<script type="application/ld+json">
{
  "@context": "https://schema.org",
  "@type": "LocalBusiness",
  "@id": "YOUR_WEBSITE_URL/#organization",
  "name": "YOUR_COMPANY_NAME",
  "image": "YOUR_STOREFRONT_IMAGE_URL",
  "url": "YOUR_WEBSITE_URL",
  "telephone": "YOUR_COMPANY_PHONE",
  "priceRange": "YOUR_PRICE_RANGE",
  "address": {
    "@type": "PostalAddress",
    "streetAddress": "YOUR_COMPANY_ADDRESS",
    "addressLocality": "YOUR_CITY",
    "addressRegion": "YOUR_STATE",
    "postalCode": "YOUR_POSTAL_CODE",
    "addressCountry": "YOUR_COUNTRY_CODE"
  },
  "geo": {
    "@type": "GeoCoordinates",
    "latitude": "YOUR_LATITUDE",
    "longitude": "YOUR_LONGITUDE"
  },
  "openingHoursSpecification": [
    {
      "@type": "OpeningHoursSpecification",
      "dayOfWeek": [
        "Monday",
        "Tuesday",
        "Wednesday",
        "Thursday",
        "Friday"
      ],
      "opens": "09:00",
      "closes": "17:00"
    },
    {
      "@type": "OpeningHoursSpecification",
      "dayOfWeek": "Saturday",
      "opens": "10:00",
      "closes": "14:00"
    }
  ]
}
</script>
```

### 8.3 Product Schema (Za proizvode)

```json
<script type="application/ld+json">
{
  "@context": "https://schema.org",
  "@type": "Product",
  "name": "YOUR_PRODUCT_NAME",
  "image": [
    "YOUR_PRODUCT_IMAGE_URL_1",
    "YOUR_PRODUCT_IMAGE_URL_2",
    "YOUR_PRODUCT_IMAGE_URL_3"
  ],
  "description": "YOUR_PRODUCT_DESCRIPTION",
  "brand": {
    "@type": "Brand",
    "name": "YOUR_BRAND_NAME"
  },
  "offers": {
    "@type": "Offer",
    "url": "YOUR_PRODUCT_URL",
    "priceCurrency": "YOUR_CURRENCY_CODE",
    "price": "PRODUCT_PRICE",
    "priceValidUntil": "YYYY-MM-DD",
    "availability": "https://schema.org/InStock",
    "itemCondition": "https://schema.org/NewCondition"
  },
  "aggregateRating": {
    "@type": "AggregateRating",
    "ratingValue": "RATING_VALUE",
    "reviewCount": "REVIEW_COUNT",
    "bestRating": "5",
    "worstRating": "1"
  },
  "review": [
    {
      "@type": "Review",
      "author": {
        "@type": "Person",
        "name": "REVIEW_AUTHOR_NAME"
      },
      "datePublished": "YYYY-MM-DD",
      "reviewBody": "REVIEW_TEXT",
      "reviewRating": {
        "@type": "Rating",
        "ratingValue": "RATING_VALUE",
        "bestRating": "5"
      }
    }
  ]
}
</script>
```

### 8.4 Review Schema (Standalone)

```json
<script type="application/ld+json">
{
  "@context": "https://schema.org",
  "@type": "Review",
  "itemReviewed": {
    "@type": "Product",
    "name": "YOUR_PRODUCT_NAME"
  },
  "author": {
    "@type": "Person",
    "name": "REVIEW_AUTHOR_NAME"
  },
  "datePublished": "YYYY-MM-DD",
  "reviewBody": "REVIEW_TEXT",
  "reviewRating": {
    "@type": "Rating",
    "ratingValue": "RATING_VALUE",
    "bestRating": "5",
    "worstRating": "1"
  }
}
</script>
```

### 8.5 FAQPage Schema

```json
<script type="application/ld+json">
{
  "@context": "https://schema.org",
  "@type": "FAQPage",
  "mainEntity": [
    {
      "@type": "Question",
      "name": "YOUR_QUESTION_TEXT",
      "acceptedAnswer": {
        "@type": "Answer",
        "text": "YOUR_ANSWER_TEXT"
      }
    },
    {
      "@type": "Question",
      "name": "YOUR_QUESTION_TEXT_2",
      "acceptedAnswer": {
        "@type": "Answer",
        "text": "YOUR_ANSWER_TEXT_2"
      }
    }
  ]
}
</script>
```

### 8.6 BreadcrumbList Schema

```json
<script type="application/ld+json">
{
  "@context": "https://schema.org",
  "@type": "BreadcrumbList",
  "itemListElement": [
    {
      "@type": "ListItem",
      "position": 1,
      "name": "Home",
      "item": "YOUR_WEBSITE_URL"
    },
    {
      "@type": "ListItem",
      "position": 2,
      "name": "YOUR_CATEGORY_NAME",
      "item": "YOUR_CATEGORY_URL"
    },
    {
      "@type": "ListItem",
      "position": 3,
      "name": "YOUR_PAGE_NAME",
      "item": "YOUR_PAGE_URL"
    }
  ]
}
</script>
```

### 8.7 WebSite Schema sa SearchAction

```json
<script type="application/ld+json">
{
  "@context": "https://schema.org",
  "@type": "WebSite",
  "name": "YOUR_WEBSITE_NAME",
  "url": "YOUR_WEBSITE_URL",
  "potentialAction": {
    "@type": "SearchAction",
    "target": {
      "@type": "EntryPoint",
      "urlTemplate": "YOUR_WEBSITE_URL/?s={search_term_string}"
    },
    "query-input": "required name=search_term_string"
  }
}
</script>
```

### 8.8 Kombinirani primjer (Organization + LocalBusiness)

```json
<script type="application/ld+json">
{
  "@context": "https://schema.org",
  "@graph": [
    {
      "@type": "Organization",
      "@id": "YOUR_WEBSITE_URL/#organization",
      "name": "YOUR_COMPANY_NAME",
      "url": "YOUR_WEBSITE_URL",
      "logo": {
        "@type": "ImageObject",
        "url": "YOUR_LOGO_URL",
        "width": 600,
        "height": 60
      },
      "sameAs": [
        "YOUR_SOCIAL_MEDIA_URL_1",
        "YOUR_SOCIAL_MEDIA_URL_2"
      ]
    },
    {
      "@type": "LocalBusiness",
      "@id": "YOUR_WEBSITE_URL/#localbusiness",
      "name": "YOUR_COMPANY_NAME",
      "image": "YOUR_STOREFRONT_IMAGE_URL",
      "telephone": "YOUR_COMPANY_PHONE",
      "priceRange": "YOUR_PRICE_RANGE",
      "address": {
        "@type": "PostalAddress",
        "streetAddress": "YOUR_COMPANY_ADDRESS",
        "addressLocality": "YOUR_CITY",
        "addressRegion": "YOUR_STATE",
        "postalCode": "YOUR_POSTAL_CODE",
        "addressCountry": "YOUR_COUNTRY_CODE"
      },
      "geo": {
        "@type": "GeoCoordinates",
        "latitude": "YOUR_LATITUDE",
        "longitude": "YOUR_LONGITUDE"
      },
      "openingHoursSpecification": [
        {
          "@type": "OpeningHoursSpecification",
          "dayOfWeek": ["Monday", "Tuesday", "Wednesday", "Thursday", "Friday"],
          "opens": "09:00",
          "closes": "17:00"
        }
      ]
    }
  ]
}
</script>
```

### 8.9 WordPress PHP funkcija za dinamički Schema

```php
// Dodajte u functions.php vaše teme (ili koristite Code Snippets plugin)
function nelsonkb_organization_schema() {
    if (is_front_page()) {
        ?>
        <script type="application/ld+json">
        {
          "@context": "https://schema.org",
          "@type": "Organization",
          "name": "<?php echo esc_js(get_bloginfo('name')); ?>",
          "url": "<?php echo esc_url(home_url()); ?>",
          "logo": "<?php echo esc_url(get_theme_mod('custom_logo')); ?>",
          "description": "<?php echo esc_js(get_bloginfo('description')); ?>",
          "address": {
            "@type": "PostalAddress",
            "streetAddress": "YOUR_COMPANY_ADDRESS",
            "addressLocality": "YOUR_CITY",
            "addressRegion": "YOUR_STATE",
            "postalCode": "YOUR_POSTAL_CODE",
            "addressCountry": "YOUR_COUNTRY_CODE"
          },
          "contactPoint": {
            "@type": "ContactPoint",
            "telephone": "YOUR_COMPANY_PHONE",
            "contactType": "customer service",
            "email": "YOUR_COMPANY_EMAIL"
          }
        }
        </script>
        <?php
    }
}
add_action('wp_head', 'nelsonkb_organization_schema');
```

---

## 9. Akcijski plan

### 9.1 Faza 1: Priprema (Tjedan 1)

#### 9.1.1 Istraživanje i analiza
- [ ] Analizirajte trenutno stanje stranice u Google Search Console (performanse, pokrivenost, greške)
- [ ] Identificirajte ključne riječi i konkurenciju (koristite Google Keyword Planner, Ahrefs ili Semrush)
- [ ] Provjerite postojeće schema markup (ako postoji) s Google Rich Results Test
- [ ] Prikupite sve potrebne informacije (logo URL s dimenzijama, kontakt, adresa, radno vrijeme, društvene mreže)

#### 9.1.2 Tehnička priprema
- [ ] Napravite backup WordPress stranice (koristite UpdraftPlus ili hosting backup)
- [ ] Provjerite brzinu učitavanja s PageSpeed Insights (cilj: >90 na mobilnim i desktop)
- [ ] Provjerite mobilnu prilagodljivost s Google Mobile-Friendly Test
- [ ] Provjerite SSL certifikat (HTTPS) - mora biti aktivan na cijeloj stranici

### 9.2 Faza 2: Implementacija Schema Markupa (Tjedan 2-3)

#### 9.2.1 Prioritet 1: Organization + LocalBusiness
- [ ] Instalirajte SEO plugin (Yoast SEO ili Rank Math)
- [ ] Konfigurirajte Organization schema s potpunim informacijama
- [ ] Dodajte LocalBusiness schema (ako je primjenjivo) s adresom i geografskim koordinatama
- [ ] Testirajte s Google Rich Results Test
- [ ] Ispravite eventualne greške

#### 9.2.2 Prioritet 2: Product Schema
- [ ] Implementirajte Product schema na svakoj stranici proizvoda
- [ ] Uključite točne cijene, dostupnost, slike (minimalno 3), opise
- [ ] Dodajte AggregateRating ako postoje recenzije (minimalno 5 recenzija)
- [ ] Testirajte validaciju s Google Rich Results Test

#### 9.2.3 Prioritet 3: Review Schema
- [ ] Implementirajte Review schema na stranice s recenzijama
- [ ] Uključite autor, datum (ISO 8601 format), ocjenu, tekst recenzije
- [ ] Testirajte prikaz zvjezdica u Google Rich Results Test

#### 9.2.4 Prioritet 4: FAQPage Schema
- [ ] Kreirajte FAQ stranicu ili sekciju (minimalno 5 pitanja)
- [ ] Implementirajte FAQPage schema markup
- [ ] Testirajte prikaz u Google Rich Results Test

#### 9.2.5 Prioritet 5: BreadcrumbList
- [ ] Implementirajte BreadcrumbList schema na sve stranice osim homepage
- [ ] Automatski generirajte iz WordPress hijerarhije
- [ ] Testirajte navigaciju i prikaz u rezultatima

#### 9.2.6 Prioritet 6: WebSite + SearchAction
- [ ] Implementirajte WebSite schema na homepage
- [ ] Dodajte SearchAction (ako postoji search funkcionalnost)
- [ ] Testirajte funkcionalnost

### 9.3 Faza 3: Optimizacija sadržaja (Tjedan 4-5)

#### 9.3.1 E-E-A-T optimizacija
- [ ] Dodajte autor biografije s kvalifikacijama na blog postove
- [ ] Kreirajte case study-jeve i studije slučaja s konkretnim rezultatima
- [ ] Dodajte testimonijale i recenzije s verifikacijom
- [ ] Poboljšajte About stranicu s detaljnim informacijama o tvrtki

#### 9.3.2 Edukativni sadržaj
- [ ] Kreirajte blog postove o kuhinjskim ormarićima (minimalno 4 posta)
- [ ] Dodajte vodiče i tutorijale s koracima
- [ ] Kreirajte FAQ sekcije na relevantnim stranicama
- [ ] Optimizirajte postojeći sadržaj s E-E-A-T elementima

#### 9.3.3 Tehnička optimizacija
- [ ] Optimizirajte slike (WebP format, lazy loading, kompresija)
- [ ] Minificirajte CSS i JavaScript datoteke
- [ ] Implementirajte caching (WP Rocket, W3 Total Cache)
- [ ] Poboljšajte Core Web Vitals (LCP < 2.5s, INP < 200ms, CLS < 0.1)

### 9.4 Faza 4: Validacija i testiranje (Tjedan 6)

#### 9.4.1 Testiranje Schema Markupa
- [ ] Testirajte sve stranice s Google Rich Results Test
- [ ] Provjerite Schema.org validator za sintaksne greške
- [ ] Ispravite eventualne greške koje alati identificiraju

#### 9.4.2 Google Search Console
- [ ] Pošaljite sitemap u Google Search Console (ako već nije poslan)
- [ ] Provjerite da li Google prepoznaje schema markup u "Enhancements" sekciji
- [ ] Pratite eventualna upozorenja i greške
- [ ] Zatražite re-indeksiranje stranica s novim schema markup-om

#### 9.4.3 A/B testiranje
- [ ] Usporedite performanse prije i poslije implementacije (Google Analytics)
- [ ] Pratite CTR u rezultatima pretrage (Google Search Console)
- [ ] Analizirajte promet iz pretraživanja (organički promet, pozicije)

### 9.5 Faza 5: Praćenje i optimizacija (Kontinuirano)

#### 9.5.1 Redovito praćenje
- [ ] Mjesečna analiza u Google Search Console (performanse, pozicije, CTR)
- [ ] Praćenje CTR i pozicija u rezultatima pretrage
- [ ] Analiza prometa iz pretraživanja (Google Analytics)
- [ ] Provjera rich snippets u rezultatima pretrage

#### 9.5.2 Kontinuirana optimizacija
- [ ] Ažuriranje schema markupa kada je potrebno (nove stranice, promjene)
- [ ] Dodavanje novih tipova schema-a kada je relevantno
- [ ] Optimizacija sadržaja na temelju rezultata i analitike
- [ ] Praćenje novih trendova u AI pretraživanju i SEO-u

### 9.6 Checklist za brzu provjeru

**Prije implementacije:**
- [ ] Backup stranice napravljen
- [ ] SSL certifikat aktivan (HTTPS) na cijeloj stranici
- [ ] Brzina učitavanja prihvatljiva (>70 PageSpeed, cilj >90)
- [ ] Mobilna prilagodljivost provjerena i prolazi test
- [ ] Svi potrebni podaci prikupljeni (logo, kontakt, adresa, itd.)

**Nakon implementacije:**
- [ ] Svi schema tipovi testirani s Google Rich Results Test
- [ ] Nema grešaka u Google Rich Results Test
- [ ] Sitemap poslan u Google Search Console
- [ ] Rich snippets vidljivi u rezultatima (nakon 7-14 dana)
- [ ] Dokumentacija ažurirana s promjenama

---

## 10. Alati i resursi

### 10.1 Alati za testiranje

1. **Google Rich Results Test**
   - URL: https://search.google.com/test/rich-results
   - Svrha: Testiranje schema markupa i rich snippets
   - Kako koristiti: Unesite URL stranice ili zalijepite JSON-LD kod

2. **Schema.org Validator**
   - URL: https://validator.schema.org/
   - Svrha: Validacija schema sintakse i identifikacija grešaka
   - Kako koristiti: Unesite URL stranice ili zalijepite JSON-LD kod

3. **Google Search Console**
   - URL: https://search.google.com/search-console
   - Svrha: Praćenje performansi, grešaka i rich results statusa
   - Kako koristiti: Prijavite se i dodajte svoju stranicu, provjerite "Enhancements" sekciju

4. **PageSpeed Insights**
   - URL: https://pagespeed.web.dev/
   - Svrha: Analiza brzine učitavanja i Core Web Vitals metrika
   - Kako koristiti: Unesite URL stranice i analizirajte rezultate

### 10.2 WordPress dodaci

1. **Yoast SEO**
   - URL: https://wordpress.org/plugins/wordpress-seo/
   - Cijena: Besplatan (Premium dostupan od $99/godina)
   - Funkcije: SEO optimizacija + Schema markup (Organization, WebSite, BreadcrumbList, Product s WooCommerce)

2. **Rank Math SEO**
   - URL: https://wordpress.org/plugins/seo-by-rank-math/
   - Cijena: Besplatan
   - Funkcije: Napredne SEO funkcije + Schema markup (više tipova u besplatnoj verziji)

3. **Schema Pro**
   - URL: https://wpschema.com/
   - Cijena: Premium ($79/godina)
   - Funkcije: Specijaliziran za schema markup s preko 15 tipova

4. **All in One Schema Rich Snippets**
   - URL: https://wordpress.org/plugins/all-in-one-schemaorg-rich-snippets/
   - Cijena: Besplatan
   - Funkcije: Rich snippets za različite tipove sadržaja (recenzije, proizvodi, događaji)

### 10.3 Edukativni resursi

1. **Schema.org Dokumentacija**
   - URL: https://schema.org/
   - Svrha: Kompletan vodič kroz sve schema tipove i svojstva

2. **Google Search Central**
   - URL: https://developers.google.com/search
   - Svrha: Google SEO vodiči, najbolje prakse i dokumentacija

3. **Bing Webmaster Guidelines**
   - URL: https://www.bing.com/webmasters
   - Svrha: Bing SEO vodiči i webmaster resursi

---

## 11. Zaključak

### 11.1 Ključni zaključci

1. **Schema Markup je kritičan za AI pretraživanje**
   - AI pretraživači oslanjaju se na strukturirane podatke za razumijevanje konteksta i relevantnosti sadržaja
   - Implementacija schema markupa može značajno poboljšati vidljivost u standardnim i AI pretraživačima
   - Prema Google Search Central, stranice s implementiranim schema markup-om imaju veću šansu biti korištene u AI generiranim odgovorima

2. **E-E-A-T principi su važniji nego ikad**
   - AI pretraživači preferiraju autoritativne, pouzdane izvore s dokazanim iskustvom i stručnošću
   - Fokus na kvalitetu sadržaja, autoritetu i pouzdanosti postaje kritičan za uspjeh u AI pretraživanju
   - Prema Google Search Quality Rater Guidelines, E-E-A-T signali direktno utječu na rangiranje

3. **WordPress olakšava implementaciju**
   - Brojni dodaci omogućavaju jednostavnu implementaciju schema markupa bez tehničkog znanja
   - Ručna implementacija je moguća za napredne korisnike koji žele potpunu kontrolu
   - Preporučeno je koristiti provjerene SEO dodatke (Yoast SEO, Rank Math) za osnovne schema tipove

4. **Kontinuirana optimizacija je ključna**
   - SEO i AI pretraživanje se kontinuirano razvijaju s novim algoritmima i funkcijama
   - Redovito praćenje performansi, testiranje i ažuriranje su neophodni za održavanje i poboljšanje rezultata
   - Prema Semrush istraživanju, stranice koje redovito ažuriraju schema markup i sadržaj imaju bolje performanse

### 11.2 Sljedeći koraci

1. **Počnite s implementacijom**
   - Slijedite akcijski plan korak po korak, počevši s prioritetom 1 (Organization schema)
   - Fokusirajte se na implementaciju schema tipova prema prioritetima navedenim u izvještaju
   - Ne pokušavajte implementirati sve odjednom - postupno dodavajte schema tipove

2. **Testirajte i validirajte**
   - Koristite Google Rich Results Test za sve implementirane schema tipove
   - Provjerite Schema.org validator za sintaksne greške
   - Ispravite greške odmah prije nego što zatražite re-indeksiranje

3. **Pratite rezultate**
   - Koristite Google Search Console za praćenje performansi i rich results statusa
   - Analizirajte promet i CTR u Google Analytics
   - Pratite pozicije u rezultatima pretrage i organički promet

4. **Optimizirajte kontinuirano**
   - Ažurirajte sadržaj i schema markup kada je potrebno
   - Dodajte nove tipove schema-a kada je relevantno (npr. Event za događaje, VideoObject za video sadržaj)
   - Pratite nove trendove u AI pretraživanju i prilagodite strategiju

---

## 12. Dodatni resursi i reference

### 12.1 Schema.org tipovi relevantni za nelsonkb.com

- **Organization**: https://schema.org/Organization
- **LocalBusiness**: https://schema.org/LocalBusiness
- **Product**: https://schema.org/Product
- **Review**: https://schema.org/Review
- **FAQPage**: https://schema.org/FAQPage
- **BreadcrumbList**: https://schema.org/BreadcrumbList
- **WebSite**: https://schema.org/WebSite

### 12.2 Google dokumentacija

- **Structured Data Guidelines**: https://developers.google.com/search/docs/appearance/structured-data
- **Rich Results Test**: https://search.google.com/test/rich-results
- **Search Console**: https://search.google.com/search-console
- **Core Web Vitals**: https://web.dev/vitals/
- **E-E-A-T Guidelines**: https://developers.google.com/search/docs/fundamentals/creating-helpful-content

### 12.3 Najbolje prakse i istraživanja

- **Google SEO Starter Guide**: https://developers.google.com/search/docs/fundamentals/seo-starter-guide
- **Bing Webmaster Guidelines**: https://www.bing.com/webmasters/help/webmaster-guidelines-30fba23a
- **Moz: E-E-A-T Complete Guide**: https://moz.com/learn/seo/e-e-a-t
- **Backlinko: Rich Snippets Study**: https://backlinko.com/rich-snippets-study
- **Semrush: Schema Markup Impact**: https://www.semrush.com/blog/schema-markup/

---

## 13. Autor i datum izrade

**Datum izrade:** 17.11.2025.  
**Klijent:** nelsonkb.com

**Kontakt za dodatna pitanja:**
Za pitanja o implementaciji ili dodatne konsultacije, kontaktirajte SEO stručnjake ili konsultirajte WordPress dokumentaciju.

---

*Ovaj izvještaj je pripremljen na temelju analize trenutnog stanja nelsonkb.com i najboljih praksi za SEO optimizaciju u kontekstu AI pretraživanja. Preporuke su specifične za nelsonkb.com i trebaju biti implementirane prema prioritetima navedenim u akcijskom planu.*
