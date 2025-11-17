# SEO i AI Search Analiza za nelsonkb.com
## Strukturirani izvještaj o poboljšanju vidljivosti u kontekstu AI pretraživanja

---

## 📋 Sadržaj

1. [Uvod i kontekst](#uvod-i-kontekst)
2. [AI pretraživanje - trendovi i utjecaj](#ai-pretraživanje---trendovi-i-utjecaj)
3. [Schema Markup - detaljno objašnjenje](#schema-markup---detaljno-objašnjenje)
4. [SEO optimizacija za AI pretraživače](#seo-optimizacija-za-ai-pretraživače)
5. [Konkretne preporuke za nelsonkb.com](#konkretne-preporuke-za-nelsonkbcom)
6. [Implementacija u WordPress](#implementacija-u-wordpress)
7. [Primjeri koda](#primjeri-koda)
8. [Akcijski plan](#akcijski-plan)

---

## 1. Uvod i kontekst

### 1.1 Cilj izvještaja
Ovaj izvještaj pruža sveobuhvatan pregled strategija za poboljšanje SEO performansi i vidljivosti web stranice **nelsonkb.com** u kontekstu rastućeg trenda AI pretraživanja. Fokus je na implementaciji strukturiranih podataka (Schema Markup) i optimizaciji za nove AI pretraživače poput Google SGE (Search Generative Experience) i Bing Copilot.

### 1.2 Kontekst AI pretraživanja
Tradicionalno SEO se temelji na optimizaciji za ljudske korisnike, ali s pojavom AI pretraživača, potrebno je prilagoditi strategiju kako bi se osiguralo da AI sustavi mogu točno interpretirati i prikazati sadržaj.

---

## 2. AI pretraživanje - trendovi i utjecaj

### 2.1 Google SGE (Search Generative Experience)

**Što je Google SGE?**
Google SGE je eksperimentalna funkcija koja koristi generativnu AI tehnologiju za pružanje direktnih odgovora na upite korisnika, često bez potrebe za klikom na web stranicu.

**Ključne karakteristike:**
- **Generativni odgovori:** AI generira sažetke i odgovore temeljene na više izvora
- **Konverzacijski pristup:** Korisnici mogu postavljati follow-up pitanja
- **Vizualni prikaz:** Uključuje slike, grafikone i interaktivne elemente
- **Izvori informacija:** Prikazuje izvore iz kojih je informacija preuzeta

**Utjecaj na SEO:**
- **Smanjenje organičkog prometa:** Korisnici dobivaju odgovore direktno u rezultatima
- **Povećana važnost autoriteta:** AI preferira pouzdane, autoritativne izvore
- **Strukturirani podaci su ključni:** Schema markup pomaže AI sustavima razumjeti kontekst

### 2.2 Bing Copilot (Microsoft)

**Što je Bing Copilot?**
Bing Copilot integrira AI asistenta direktno u pretraživanje, omogućavajući konverzacijsko pretraživanje s kontekstualnim odgovorima.

**Ključne karakteristike:**
- **Integrirani AI asistent:** Dostupan direktno u pretraživaču
- **Multi-modalni pristup:** Kombinira tekst, slike i video
- **Kontekstualno razumijevanje:** Razumije složene upite i follow-up pitanja
- **Real-time informacije:** Koristi najnovije dostupne informacije

**Utjecaj na SEO:**
- **Fokus na E-E-A-T:** Experience, Expertise, Authoritativeness, Trustworthiness
- **Strukturirani sadržaj:** Bolje strukturirani sadržaj = bolje razumijevanje od strane AI
- **Lokalni SEO:** Posebno važno za poslovne stranice

### 2.3 Ključne razlike u odnosu na tradicionalno SEO

| Aspekt | Tradicionalno SEO | AI Search SEO |
|--------|-------------------|---------------|
| **Ciljna publika** | Ljudski korisnici | AI sustavi + ljudski korisnici |
| **Fokus** | Ključne riječi | Kontekst i semantika |
| **Strukturirani podaci** | Opcionalni | Obavezni |
| **Autoritet** | Važan | Kritičan |
| **Sadržaj** | Optimiziran za ljude | Optimiziran za AI razumijevanje |

---

## 3. Schema Markup - detaljno objašnjenje

### 3.1 Što je Schema Markup?

**Definicija:**
Schema Markup (također poznat kao strukturirani podaci ili structured data) je kod koji se dodaje na web stranicu kako bi se pomoglo pretraživačima da bolje razumiju sadržaj stranice. Koristi se standardizirani vokabular definiran na **schema.org**.

**Kako funkcionira:**
1. **Dodavanje koda:** Strukturirani podaci se dodaju u HTML stranice
2. **Čitanje od strane pretraživača:** Google, Bing i drugi pretraživači čitaju ove podatke
3. **Razumijevanje konteksta:** Pretraživači bolje razumiju što stranica predstavlja
4. **Poboljšani prikaz:** Rezultati pretrage mogu prikazati bogate isječke (rich snippets)

### 3.2 Zašto je Schema Markup koristan za SEO?

#### 3.2.1 Poboljšana vidljivost u rezultatima pretrage

**Rich Snippets (Bogati isječci):**
- **Zvjezdice za recenzije:** Prikaz ocjena direktno u rezultatima
- **Breadcrumbs:** Navigacijski put prikazan u rezultatima
- **FAQ isječci:** Odgovori na česta pitanja prikazani direktno
- **Event informacije:** Datum, vrijeme i lokacija događaja
- **Proizvodi:** Cijena, dostupnost, ocjene

**Primjer:**
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

#### 3.2.2 Povećana stopa klikanja (CTR)

**Statistike:**
- Rich snippets mogu povećati CTR za **30-50%**
- Korisnici su skloniji kliknuti na rezultate s dodatnim informacijama
- Vizualno privlačniji rezultati privlače više pažnje

#### 3.2.3 Bolje razumijevanje od strane AI sustava

**Za AI pretraživače:**
- AI sustavi koriste strukturirane podatke za razumijevanje konteksta
- Omogućava točnije odgovore na upite korisnika
- Povećava šanse da vaš sadržaj bude korišten u AI generiranim odgovorima

#### 3.2.4 Poboljšano rangiranje

**Indirektni utjecaj:**
- Iako Schema markup nije direktan ranking faktor, poboljšava:
  - CTR (click-through rate) → pozitivan signal za Google
  - Korisničko iskustvo → bolje engagement metrike
  - Razumijevanje sadržaja → točnije kategoriziranje

### 3.3 Formati Schema Markupa

#### 3.3.1 JSON-LD (Preporučeno)

**Prednosti:**
- ✅ Najlakši za implementaciju
- ✅ Ne utječe na HTML strukturu
- ✅ Lako održavanje
- ✅ Preporučeno od strane Google-a

**Primjer:**
```json
<script type="application/ld+json">
{
  "@context": "https://schema.org",
  "@type": "Organization",
  "name": "Nelson Cabinetry",
  "url": "https://nelsonkb.com",
  "logo": "https://nelsonkb.com/logo.png"
}
</script>
```

#### 3.3.2 Microdata

**Karakteristike:**
- Integrirano direktno u HTML elemente
- Može komplicirati HTML kod
- Teže za održavanje

**Primjer:**
```html
<div itemscope itemtype="https://schema.org/Organization">
  <span itemprop="name">Nelson Cabinetry</span>
  <span itemprop="url">https://nelsonkb.com</span>
</div>
```

#### 3.3.3 RDFa

**Karakteristike:**
- Slično Microdata, ali koristi RDF sintaksu
- Rijetko korišten
- Kompleksniji za implementaciju

### 3.4 Najvažniji tipovi Schema Markupa za nelsonkb.com

#### 3.4.1 Organization (Organizacija)
**Svrha:** Definira informacije o tvrtki

**Ključna svojstva:**
- `name` - Naziv tvrtke
- `url` - URL web stranice
- `logo` - Logo tvrtke
- `description` - Opis poslovanja
- `address` - Adresa
- `contactPoint` - Kontakt informacije
- `sameAs` - Linkovi na društvene mreže

#### 3.4.2 LocalBusiness (Lokalni posao)
**Svrha:** Za lokalne poslove s fizičkom lokacijom

**Ključna svojstva:**
- `address` - Potpuna adresa
- `geo` - Geografske koordinate
- `openingHours` - Radno vrijeme
- `priceRange` - Cjenovni rang
- `telephone` - Telefonski broj

#### 3.4.3 Product (Proizvod)
**Svrha:** Za proizvode u e-commerce trgovini

**Ključna svojstva:**
- `name` - Naziv proizvoda
- `description` - Opis proizvoda
- `image` - Slike proizvoda
- `offers` - Cijena i dostupnost
- `brand` - Marka proizvoda
- `aggregateRating` - Prosječna ocjena

#### 3.4.4 Review (Recenzija)
**Svrha:** Za prikaz recenzija proizvoda/usluga

**Ključna svojstva:**
- `author` - Autor recenzije
- `datePublished` - Datum objave
- `reviewBody` - Tekst recenzije
- `reviewRating` - Ocjena (1-5)

#### 3.4.5 FAQPage (Česta pitanja)
**Svrha:** Za stranice s čestim pitanjima

**Ključna svojstva:**
- `mainEntity` - Lista pitanja i odgovora
- `question` - Tekst pitanja
- `acceptedAnswer` - Tekst odgovora

#### 3.4.6 BreadcrumbList (Navigacijski put)
**Svrha:** Za prikaz navigacijskog puta

**Ključna svojstva:**
- `itemListElement` - Lista elemenata u navigaciji
- `position` - Pozicija u hijerarhiji
- `name` - Naziv stranice
- `item` - URL stranice

#### 3.4.7 WebSite (Web stranica)
**Svrha:** Opće informacije o web stranici

**Ključna svojstva:**
- `name` - Naziv stranice
- `url` - URL stranice
- `potentialAction` - Akcije (npr. pretraživanje)

---

## 4. SEO optimizacija za AI pretraživače

### 4.1 E-E-A-T principi (Experience, Expertise, Authoritativeness, Trustworthiness)

**Zašto je E-E-A-T važan za AI pretraživanje?**

AI pretraživači koriste E-E-A-T signale za određivanje pouzdanosti izvora. Stranice s visokim E-E-A-T-om imaju veće šanse biti korištene u AI generiranim odgovorima.

#### 4.1.1 Experience (Iskustvo)
- **Što je:** Praktično iskustvo s temom
- **Kako implementirati:**
  - Blog postovi temeljeni na stvarnom iskustvu
  - Case study-ji i studije slučaja
  - Korisničke priče i testimonijali

#### 4.1.2 Expertise (Stručnost)
- **Što je:** Duboko znanje o temi
- **Kako implementirati:**
  - Detaljni vodiči i tutorijali
  - Tehnički sadržaj
  - Objašnjenja složenih koncepata
  - Autor biografije s kvalifikacijama

#### 4.1.3 Authoritativeness (Autoritet)
- **Što je:** Prepoznatljivost i utjecaj u industriji
- **Kako implementirati:**
  - Linkovi s drugih autoritativnih stranica
  - Spominjanje u medijima
  - Nagrade i priznanja
  - Članstvo u profesionalnim organizacijama

#### 4.1.4 Trustworthiness (Pouzdanost)
- **Što je:** Povjerenje korisnika
- **Kako implementirati:**
  - Transparentne kontakt informacije
  - Pravila privatnosti i uvjeti korištenja
  - SSL certifikat (HTTPS)
  - Recenzije i ocjene korisnika

### 4.2 Optimizacija sadržaja za AI

#### 4.2.1 Semantički HTML
- Koristite ispravne HTML5 elemente (`<article>`, `<section>`, `<header>`, `<nav>`)
- Strukturirana hijerarhija naslova (H1 → H2 → H3)
- Smisleni alt tekstovi za slike

#### 4.2.2 Kontekstualni sadržaj
- Odgovarajte na pitanja korisnika direktno u sadržaju
- Koristite prirodni jezik umjesto keyword stuffing-a
- Uključite relevantne informacije koje AI može izvući

#### 4.2.3 Strukturirani format
- Koristite liste i tablice za organizaciju informacija
- Kratki paragrafi s jasnim naslovima
- FAQ sekcije za česta pitanja

### 4.3 Tehnička optimizacija

#### 4.3.1 Brzina učitavanja
- **Cilj:** PageSpeed Score > 90
- Optimizacija slika (WebP format, lazy loading)
- Minifikacija CSS i JavaScript
- Keširanje (caching)
- CDN (Content Delivery Network)

#### 4.3.2 Mobilna prilagodljivost
- **Cilj:** Mobile-friendly test = Pass
- Responzivni dizajn
- Touch-friendly elementi
- Brzo učitavanje na mobilnim uređajima

#### 4.3.3 Core Web Vitals
- **LCP (Largest Contentful Paint):** < 2.5s
- **FID (First Input Delay):** < 100ms
- **CLS (Cumulative Layout Shift):** < 0.1

---

## 5. Konkretne preporuke za nelsonkb.com

### 5.1 Analiza trenutnog stanja (preporuke)

**Pretpostavke o nelsonkb.com:**
- Web stranica za Nelson Cabinetry (proizvođač kuhinjskih ormarića)
- E-commerce ili B2B fokus
- Lokalni ili nacionalni posao

### 5.2 Prioritetne implementacije Schema Markupa

#### Prioritet 1: Organization + LocalBusiness
**Zašto:** Osnovne informacije o tvrtki su kritične za lokalni SEO i AI pretraživanje.

**Implementacija:**
- Dodati na homepage
- Uključiti kontakt informacije, adresu, radno vrijeme
- Linkovi na društvene mreže

#### Prioritet 2: Product Schema
**Zašto:** Ako stranica prodaje proizvode, Product schema je obavezan za prikaz cijena i dostupnosti.

**Implementacija:**
- Na svakoj stranici proizvoda
- Uključiti cijene, dostupnost, slike, opise
- AggregateRating ako postoje recenzije

#### Prioritet 3: Review Schema
**Zašto:** Recenzije su snažan signal pouzdanosti i mogu rezultirati zvjezdicama u rezultatima.

**Implementacija:**
- Na stranicama proizvoda s recenzijama
- Na homepage ako postoje testimonijali
- Uključiti autor, datum, ocjenu, tekst

#### Prioritet 4: FAQPage
**Zašto:** FAQ stranice su idealne za AI pretraživanje jer direktno odgovaraju na pitanja.

**Implementacija:**
- Na FAQ stranici
- Na stranicama proizvoda s čestim pitanjima
- Strukturirati kao pitanje-odgovor parovi

#### Prioritet 5: BreadcrumbList
**Zašto:** Poboljšava navigaciju i može se prikazati u rezultatima pretrage.

**Implementacija:**
- Na svim stranicama osim homepage
- Automatski generirati iz WordPress hijerarhije

#### Prioritet 6: WebSite + SearchAction
**Zašto:** Omogućava Google-u da prikaže search box u rezultatima.

**Implementacija:**
- Na homepage
- Uključiti SearchAction ako postoji search funkcionalnost

### 5.3 Optimizacija sadržaja

#### 5.3.1 Blog i edukativni sadržaj
**Preporuke:**
- "Kako odabrati kuhinjske ormariće" - vodič
- "RTA vs Custom Cabinets: Što je bolje?" - usporedba
- "10 najčešćih grešaka pri instalaciji ormarića" - edukativni sadržaj
- "Trenutni trendovi u kuhinjskim dizajnu 2024" - trendovi

**Zašto:** Edukativni sadržaj privlači AI pretraživače koji traže odgovore na pitanja.

#### 5.3.2 FAQ sekcije
**Preporuke:**
- Dodati FAQ sekciju na homepage
- FAQ na stranicama kategorija proizvoda
- FAQ na stranicama proizvoda

**Primjeri pitanja:**
- "Što je RTA cabinet?"
- "Koliko koštaju kuhinjski ormarići?"
- "Kako se instaliraju RTA ormarići?"
- "Koja je razlika između soft-close i standardnih ormarića?"

### 5.4 Lokalni SEO (ako je primjenjivo)

**Ako je Nelson Cabinetry lokalni posao:**
- Implementirati LocalBusiness schema
- Google Business Profile optimizacija
- Lokalni linkovi i citati
- Lokalni sadržaj (npr. "Kuhinjski ormarići u [grad]")

---

## 6. Implementacija u WordPress

### 6.1 Metode implementacije

#### Metoda 1: Korištenje dodataka (Preporučeno za većinu korisnika)

**Prednosti:**
- ✅ Lako za korištenje
- ✅ Bez potrebe za kodiranjem
- ✅ Automatska validacija
- ✅ Redovna ažuriranja

**Najbolji dodaci za Schema Markup:**

##### 6.1.1 Yoast SEO (Najpopularniji)
**Karakteristike:**
- Besplatan i premium verzija
- Automatski dodaje osnovne schema tipove
- Lako konfiguriranje kroz interfejs
- Integracija s drugim SEO funkcijama

**Kako koristiti:**
1. Instalirajte Yoast SEO
2. Idite na SEO → Search Appearance
3. Konfigurirajte Organization schema
4. Za proizvode, koristite WooCommerce integraciju

##### 6.1.2 Rank Math SEO
**Karakteristike:**
- Besplatan s naprednim funkcijama
- Više schema tipova u besplatnoj verziji
- Intuitivno sučelje
- Automatska detekcija tipa sadržaja

**Kako koristiti:**
1. Instalirajte Rank Math SEO
2. Idite na Rank Math → General Settings
3. Konfigurirajte Company Info
4. Omogućite automatski schema generation

##### 6.1.3 Schema Pro (Premium)
**Karakteristike:**
- Specijaliziran za schema markup
- Preko 15 različitih schema tipova
- Drag-and-drop builder
- Detaljna kontrola

**Kako koristiti:**
1. Instalirajte Schema Pro
2. Odaberite tip sadržaja
3. Popunite potrebna polja
4. Spremite i objavite

##### 6.1.4 All in One Schema Rich Snippets
**Karakteristike:**
- Besplatan
- Fokus na rich snippets
- Jednostavno za korištenje
- Podrška za različite tipove sadržaja

**Kako koristiti:**
1. Instalirajte plugin
2. Odaberite tip rich snippet-a
3. Popunite informacije
4. Spremite

#### Metoda 2: Ručna implementacija (Za napredne korisnike)

**Prednosti:**
- ✅ Potpuna kontrola
- ✅ Nema ovisnosti o dodacima
- ✅ Optimizirano za specifične potrebe

**Nedostaci:**
- ❌ Zahtijeva tehničko znanje
- ❌ Teže održavanje
- ❌ Rizik od grešaka

**Gdje dodati kod:**

##### Opcija A: U WordPress temi (functions.php)
```php
// Dodajte u functions.php vaše teme
function add_schema_markup() {
    ?>
    <script type="application/ld+json">
    {
      "@context": "https://schema.org",
      "@type": "Organization",
      "name": "Nelson Cabinetry",
      "url": "https://nelsonkb.com",
      "logo": "https://nelsonkb.com/logo.png",
      "description": "Premium RTA kitchen cabinets and cabinetry solutions"
    }
    </script>
    <?php
}
add_action('wp_head', 'add_schema_markup');
```

##### Opcija B: Kroz WordPress Customizer
- Idite na Appearance → Customize → Additional CSS
- Dodajte kod u "Additional Head Code" sekciju (ako postoji)

##### Opcija C: Kroz plugin za custom code
- Koristite plugin poput "Insert Headers and Footers"
- Dodajte JSON-LD kod u header sekciju

### 6.2 Korak-po-korak vodič za implementaciju

#### Korak 1: Priprema
1. **Backup stranice** - Napravite backup prije bilo kakvih promjena
2. **Odaberite metodu** - Dodatak ili ručna implementacija
3. **Prikupljanje informacija** - Pripremite sve potrebne podatke

#### Korak 2: Implementacija Organization Schema
1. Instalirajte odabrani plugin (npr. Yoast SEO)
2. Konfigurirajte osnovne informacije o tvrtki
3. Dodajte logo URL
4. Dodajte kontakt informacije
5. Spremite promjene

#### Korak 3: Implementacija Product Schema (ako je primjenjivo)
1. Ako koristite WooCommerce, omogućite schema u WooCommerce postavkama
2. Za ručnu implementaciju, dodajte kod na stranice proizvoda
3. Uključite cijene, dostupnost, slike

#### Korak 4: Implementacija Review Schema
1. Ako koristite plugin za recenzije, provjerite podršku za schema
2. Ručno dodajte Review schema na stranice s recenzijama
3. Uključite autor, datum, ocjenu, tekst

#### Korak 5: Implementacija FAQPage Schema
1. Kreirajte FAQ stranicu ili sekciju
2. Strukturirajte kao pitanje-odgovor parove
3. Dodajte FAQPage schema markup

#### Korak 6: Testiranje
1. Koristite Google Rich Results Test
2. Provjerite sve stranice s implementiranim schema-om
3. Ispravite eventualne greške

#### Korak 7: Validacija u Google Search Console
1. Pošaljite sitemap u Google Search Console
2. Provjerite da li Google prepoznaje schema markup
3. Pratite eventualne upozorenja

### 6.3 Najbolje prakse za WordPress

#### 6.3.1 Performanse
- **Ne koristite više dodataka nego što je potrebno** - Svaki dodatak utječe na performanse
- **Koristite caching** - Schema markup se ne mijenja često, keširajte ga
- **Minifikacija** - Ako ručno dodajete kod, minificirajte ga

#### 6.3.2 Održavanje
- **Redovite provjere** - Provjeravajte schema markup nakon ažuriranja teme/dodataka
- **Ažuriranje dodataka** - Držite SEO dodatke ažurirane
- **Backup prije promjena** - Uvijek napravite backup prije većih promjena

#### 6.3.3 Validacija
- **Google Rich Results Test** - Redovito testirajte
- **Schema.org validator** - Koristite za provjeru sintakse
- **Google Search Console** - Pratite upozorenja i greške

---

## 7. Primjeri koda

### 7.1 Organization Schema (Osnovni)

```json
<script type="application/ld+json">
{
  "@context": "https://schema.org",
  "@type": "Organization",
  "name": "Nelson Cabinetry",
  "url": "https://nelsonkb.com",
  "logo": "https://nelsonkb.com/wp-content/uploads/logo.png",
  "description": "Premium RTA (Ready-to-Assemble) kitchen cabinets and cabinetry solutions. Quality craftsmanship and modern design.",
  "address": {
    "@type": "PostalAddress",
    "streetAddress": "123 Main Street",
    "addressLocality": "City",
    "addressRegion": "State",
    "postalCode": "12345",
    "addressCountry": "US"
  },
  "contactPoint": {
    "@type": "ContactPoint",
    "telephone": "+1-555-123-4567",
    "contactType": "customer service",
    "email": "info@nelsonkb.com",
    "availableLanguage": ["English", "Spanish"]
  },
  "sameAs": [
    "https://www.facebook.com/nelsoncabinetry",
    "https://www.instagram.com/nelsoncabinetry",
    "https://www.linkedin.com/company/nelsoncabinetry"
  ]
}
</script>
```

### 7.2 LocalBusiness Schema (Za lokalni posao)

```json
<script type="application/ld+json">
{
  "@context": "https://schema.org",
  "@type": "LocalBusiness",
  "@id": "https://nelsonkb.com/#organization",
  "name": "Nelson Cabinetry",
  "image": "https://nelsonkb.com/wp-content/uploads/storefront.jpg",
  "url": "https://nelsonkb.com",
  "telephone": "+1-555-123-4567",
  "priceRange": "$$",
  "address": {
    "@type": "PostalAddress",
    "streetAddress": "123 Main Street",
    "addressLocality": "City",
    "addressRegion": "State",
    "postalCode": "12345",
    "addressCountry": "US"
  },
  "geo": {
    "@type": "GeoCoordinates",
    "latitude": "40.7128",
    "longitude": "-74.0060"
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

### 7.3 Product Schema (Za proizvode)

```json
<script type="application/ld+json">
{
  "@context": "https://schema.org",
  "@type": "Product",
  "name": "Modern White Shaker Kitchen Cabinet",
  "image": [
    "https://nelsonkb.com/wp-content/uploads/cabinet-front.jpg",
    "https://nelsonkb.com/wp-content/uploads/cabinet-interior.jpg"
  ],
  "description": "Premium RTA shaker-style kitchen cabinet in modern white finish. Soft-close hinges included.",
  "brand": {
    "@type": "Brand",
    "name": "Nelson Cabinetry"
  },
  "offers": {
    "@type": "Offer",
    "url": "https://nelsonkb.com/product/modern-white-shaker-cabinet",
    "priceCurrency": "USD",
    "price": "299.99",
    "priceValidUntil": "2024-12-31",
    "availability": "https://schema.org/InStock",
    "itemCondition": "https://schema.org/NewCondition"
  },
  "aggregateRating": {
    "@type": "AggregateRating",
    "ratingValue": "4.8",
    "reviewCount": "127",
    "bestRating": "5",
    "worstRating": "1"
  },
  "review": [
    {
      "@type": "Review",
      "author": {
        "@type": "Person",
        "name": "John Smith"
      },
      "datePublished": "2024-01-15",
      "reviewBody": "Excellent quality cabinets. Easy to assemble and look great in our kitchen.",
      "reviewRating": {
        "@type": "Rating",
        "ratingValue": "5",
        "bestRating": "5"
      }
    }
  ]
}
</script>
```

### 7.4 Review Schema (Standalone)

```json
<script type="application/ld+json">
{
  "@context": "https://schema.org",
  "@type": "Review",
  "itemReviewed": {
    "@type": "Product",
    "name": "Modern White Shaker Kitchen Cabinet"
  },
  "author": {
    "@type": "Person",
    "name": "Sarah Johnson"
  },
  "datePublished": "2024-02-20",
  "reviewBody": "These cabinets exceeded my expectations. The quality is outstanding and the installation was straightforward. Highly recommend!",
  "reviewRating": {
    "@type": "Rating",
    "ratingValue": "5",
    "bestRating": "5",
    "worstRating": "1"
  }
}
</script>
```

### 7.5 FAQPage Schema

```json
<script type="application/ld+json">
{
  "@context": "https://schema.org",
  "@type": "FAQPage",
  "mainEntity": [
    {
      "@type": "Question",
      "name": "Što je RTA cabinet?",
      "acceptedAnswer": {
        "@type": "Answer",
        "text": "RTA (Ready-to-Assemble) cabinet je kuhinjski ormarić koji dolazi u pakiranju s dijelovima koje kupac sam sastavlja. Ovo omogućava niže cijene i lakši transport."
      }
    },
    {
      "@type": "Question",
      "name": "Koliko vremena treba za instalaciju RTA ormarića?",
      "acceptedAnswer": {
        "@type": "Answer",
        "text": "Instalacija standardnog seta RTA ormarića obično traje 4-8 sati, ovisno o veličini kuhinje i iskustvu instalatera. Uključuje sastavljanje, montažu i podešavanje vrata."
      }
    },
    {
      "@type": "Question",
      "name": "Koja je razlika između soft-close i standardnih ormarića?",
      "acceptedAnswer": {
        "@type": "Answer",
        "text": "Soft-close ormarići imaju mehanizam koji automatski usporava i tiho zatvara vrata kada su blizu zatvorenog položaja. Standardni ormarići zahtijevaju ručno zatvaranje i mogu proizvoditi više buke."
      }
    }
  ]
}
</script>
```

### 7.6 BreadcrumbList Schema

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
      "item": "https://nelsonkb.com"
    },
    {
      "@type": "ListItem",
      "position": 2,
      "name": "Kitchen Cabinets",
      "item": "https://nelsonkb.com/kitchen-cabinets"
    },
    {
      "@type": "ListItem",
      "position": 3,
      "name": "Shaker Style",
      "item": "https://nelsonkb.com/kitchen-cabinets/shaker-style"
    }
  ]
}
</script>
```

### 7.7 WebSite Schema sa SearchAction

```json
<script type="application/ld+json">
{
  "@context": "https://schema.org",
  "@type": "WebSite",
  "name": "Nelson Cabinetry",
  "url": "https://nelsonkb.com",
  "potentialAction": {
    "@type": "SearchAction",
    "target": {
      "@type": "EntryPoint",
      "urlTemplate": "https://nelsonkb.com/?s={search_term_string}"
    },
    "query-input": "required name=search_term_string"
  }
}
</script>
```

### 7.8 Kombinirani primjer (Organization + LocalBusiness)

```json
<script type="application/ld+json">
{
  "@context": "https://schema.org",
  "@graph": [
    {
      "@type": "Organization",
      "@id": "https://nelsonkb.com/#organization",
      "name": "Nelson Cabinetry",
      "url": "https://nelsonkb.com",
      "logo": {
        "@type": "ImageObject",
        "url": "https://nelsonkb.com/wp-content/uploads/logo.png",
        "width": 300,
        "height": 100
      },
      "sameAs": [
        "https://www.facebook.com/nelsoncabinetry",
        "https://www.instagram.com/nelsoncabinetry"
      ]
    },
    {
      "@type": "LocalBusiness",
      "@id": "https://nelsonkb.com/#localbusiness",
      "name": "Nelson Cabinetry",
      "image": "https://nelsonkb.com/wp-content/uploads/storefront.jpg",
      "telephone": "+1-555-123-4567",
      "priceRange": "$$",
      "address": {
        "@type": "PostalAddress",
        "streetAddress": "123 Main Street",
        "addressLocality": "City",
        "addressRegion": "State",
        "postalCode": "12345",
        "addressCountry": "US"
      },
      "geo": {
        "@type": "GeoCoordinates",
        "latitude": "40.7128",
        "longitude": "-74.0060"
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

### 7.9 WordPress PHP funkcija za dinamički Schema

```php
// Dodajte u functions.php vaše teme
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
            "streetAddress": "123 Main Street",
            "addressLocality": "City",
            "addressRegion": "State",
            "postalCode": "12345",
            "addressCountry": "US"
          },
          "contactPoint": {
            "@type": "ContactPoint",
            "telephone": "+1-555-123-4567",
            "contactType": "customer service",
            "email": "info@nelsonkb.com"
          }
        }
        </script>
        <?php
    }
}
add_action('wp_head', 'nelsonkb_organization_schema');
```

---

## 8. Akcijski plan

### 8.1 Faza 1: Priprema (Tjedan 1)

#### 8.1.1 Istraživanje i analiza
- [ ] Analizirajte trenutno stanje stranice (Google Search Console, Analytics)
- [ ] Identificirajte ključne riječi i konkurenciju
- [ ] Provjerite postojeće schema markup (ako postoji)
- [ ] Prikupite sve potrebne informacije (logo, kontakt, adresa, itd.)

#### 8.1.2 Tehnička priprema
- [ ] Napravite backup WordPress stranice
- [ ] Provjerite brzinu učitavanja (PageSpeed Insights)
- [ ] Provjerite mobilnu prilagodljivost
- [ ] Provjerite SSL certifikat (HTTPS)

### 8.2 Faza 2: Implementacija Schema Markupa (Tjedan 2-3)

#### 8.2.1 Prioritet 1: Organization + LocalBusiness
- [ ] Instalirajte SEO plugin (Yoast SEO ili Rank Math)
- [ ] Konfigurirajte Organization schema
- [ ] Dodajte LocalBusiness schema (ako je primjenjivo)
- [ ] Testirajte s Google Rich Results Test

#### 8.2.2 Prioritet 2: Product Schema
- [ ] Implementirajte Product schema na stranice proizvoda
- [ ] Uključite cijene, dostupnost, slike
- [ ] Testirajte validaciju

#### 8.2.3 Prioritet 3: Review Schema
- [ ] Implementirajte Review schema na stranice s recenzijama
- [ ] Uključite autor, datum, ocjenu, tekst
- [ ] Testirajte prikaz zvjezdica u rezultatima

#### 8.2.4 Prioritet 4: FAQPage Schema
- [ ] Kreirajte FAQ stranicu ili sekciju
- [ ] Implementirajte FAQPage schema
- [ ] Testirajte prikaz u rezultatima

#### 8.2.5 Prioritet 5: BreadcrumbList
- [ ] Implementirajte BreadcrumbList schema
- [ ] Testirajte navigaciju

#### 8.2.6 Prioritet 6: WebSite + SearchAction
- [ ] Implementirajte WebSite schema
- [ ] Dodajte SearchAction (ako postoji search)
- [ ] Testirajte funkcionalnost

### 8.3 Faza 3: Optimizacija sadržaja (Tjedan 4-5)

#### 8.3.1 E-E-A-T optimizacija
- [ ] Dodajte autor biografije s kvalifikacijama
- [ ] Kreirajte case study-jeve i studije slučaja
- [ ] Dodajte testimonijale i recenzije
- [ ] Poboljšajte About stranicu

#### 8.3.2 Edukativni sadržaj
- [ ] Kreirajte blog postove o kuhinjskim ormarićima
- [ ] Dodajte vodiče i tutorijale
- [ ] Kreirajte FAQ sekcije
- [ ] Optimizirajte postojeći sadržaj

#### 8.3.3 Tehnička optimizacija
- [ ] Optimizirajte slike (WebP, lazy loading)
- [ ] Minificirajte CSS i JavaScript
- [ ] Implementirajte caching
- [ ] Poboljšajte Core Web Vitals

### 8.4 Faza 4: Validacija i testiranje (Tjedan 6)

#### 8.4.1 Testiranje Schema Markupa
- [ ] Testirajte sve stranice s Google Rich Results Test
- [ ] Provjerite Schema.org validator
- [ ] Ispravite eventualne greške

#### 8.4.2 Google Search Console
- [ ] Pošaljite sitemap
- [ ] Provjerite da li Google prepoznaje schema
- [ ] Pratite upozorenja i greške
- [ ] Zatražite re-indeksiranje

#### 8.4.3 A/B testiranje
- [ ] Usporedite performanse prije i poslije
- [ ] Pratite CTR u rezultatima pretrage
- [ ] Analizirajte promet iz pretraživanja

### 8.5 Faza 5: Praćenje i optimizacija (Kontinuirano)

#### 8.5.1 Redovito praćenje
- [ ] Mjesečna analiza u Google Search Console
- [ ] Praćenje CTR i pozicija u rezultatima
- [ ] Analiza prometa iz pretraživanja
- [ ] Provjera rich snippets u rezultatima

#### 8.5.2 Kontinuirana optimizacija
- [ ] Ažuriranje schema markupa kada je potrebno
- [ ] Dodavanje novih tipova schema-a
- [ ] Optimizacija sadržaja na temelju rezultata
- [ ] Praćenje novih trendova u AI pretraživanju

### 8.6 Checklist za brzu provjeru

**Prije implementacije:**
- [ ] Backup stranice napravljen
- [ ] SSL certifikat aktivan (HTTPS)
- [ ] Brzina učitavanja prihvatljiva (>70 PageSpeed)
- [ ] Mobilna prilagodljivost provjerena
- [ ] Svi potrebni podaci prikupljeni

**Nakon implementacije:**
- [ ] Svi schema tipovi testirani
- [ ] Nema grešaka u Google Rich Results Test
- [ ] Sitemap poslan u Google Search Console
- [ ] Rich snippets vidljivi u rezultatima (nakon nekoliko dana)
- [ ] Dokumentacija ažurirana

---

## 9. Alati i resursi

### 9.1 Alati za testiranje

1. **Google Rich Results Test**
   - URL: https://search.google.com/test/rich-results
   - Svrha: Testiranje schema markupa
   - Kako koristiti: Unesite URL ili zalijepite kod

2. **Schema.org Validator**
   - URL: https://validator.schema.org/
   - Svrha: Validacija schema sintakse
   - Kako koristiti: Unesite URL ili kod

3. **Google Search Console**
   - URL: https://search.google.com/search-console
   - Svrha: Praćenje performansi i grešaka
   - Kako koristiti: Prijavite se i dodajte svoju stranicu

4. **PageSpeed Insights**
   - URL: https://pagespeed.web.dev/
   - Svrha: Analiza brzine učitavanja
   - Kako koristiti: Unesite URL stranice

### 9.2 WordPress dodaci

1. **Yoast SEO**
   - URL: https://wordpress.org/plugins/wordpress-seo/
   - Cijena: Besplatan (Premium dostupan)
   - Funkcije: SEO optimizacija + Schema markup

2. **Rank Math SEO**
   - URL: https://wordpress.org/plugins/seo-by-rank-math/
   - Cijena: Besplatan
   - Funkcije: Napredne SEO funkcije + Schema

3. **Schema Pro**
   - URL: https://wpschema.com/
   - Cijena: Premium ($79/godina)
   - Funkcije: Specijaliziran za schema markup

4. **All in One Schema Rich Snippets**
   - URL: https://wordpress.org/plugins/all-in-one-schemaorg-rich-snippets/
   - Cijena: Besplatan
   - Funkcije: Rich snippets za različite tipove

### 9.3 Edukativni resursi

1. **Schema.org Dokumentacija**
   - URL: https://schema.org/
   - Svrha: Kompletan vodič kroz schema tipove

2. **Google Search Central**
   - URL: https://developers.google.com/search
   - Svrha: Google SEO vodiči i najbolje prakse

3. **Bing Webmaster Guidelines**
   - URL: https://www.bing.com/webmasters
   - Svrha: Bing SEO vodiči

---

## 10. Zaključak

### 10.1 Ključni zaključci

1. **Schema Markup je kritičan za AI pretraživanje**
   - AI pretraživači oslanjaju se na strukturirane podatke za razumijevanje konteksta
   - Implementacija schema markupa može značajno poboljšati vidljivost

2. **E-E-A-T principi su važniji nego ikad**
   - AI pretraživači preferiraju autoritativne, pouzdane izvore
   - Fokus na kvalitetu sadržaja i autoritetu

3. **WordPress olakšava implementaciju**
   - Brojni dodaci omogućavaju jednostavnu implementaciju
   - Ručna implementacija je moguća za napredne korisnike

4. **Kontinuirana optimizacija je ključna**
   - SEO i AI pretraživanje se kontinuirano razvijaju
   - Redovito praćenje i ažuriranje su neophodni

### 10.2 Sljedeći koraci

1. **Počnite s implementacijom**
   - Slijedite akcijski plan korak po korak
   - Fokusirajte se na prioritete

2. **Testirajte i validirajte**
   - Koristite alate za testiranje
   - Ispravite greške odmah

3. **Pratite rezultate**
   - Koristite Google Search Console
   - Analizirajte promet i CTR

4. **Optimizirajte kontinuirano**
   - Ažurirajte sadržaj
   - Dodajte nove tipove schema-a kada je potrebno

---

## 11. Dodatni resursi i reference

### 11.1 Schema.org tipovi relevantni za nelsonkb.com

- **Organization**: https://schema.org/Organization
- **LocalBusiness**: https://schema.org/LocalBusiness
- **Product**: https://schema.org/Product
- **Review**: https://schema.org/Review
- **FAQPage**: https://schema.org/FAQPage
- **BreadcrumbList**: https://schema.org/BreadcrumbList
- **WebSite**: https://schema.org/WebSite

### 11.2 Google dokumentacija

- **Structured Data Guidelines**: https://developers.google.com/search/docs/appearance/structured-data
- **Rich Results Test**: https://search.google.com/test/rich-results
- **Search Console**: https://search.google.com/search-console

### 11.3 Najbolje prakse

- **Google SEO Starter Guide**: https://developers.google.com/search/docs/fundamentals/seo-starter-guide
- **Bing Webmaster Guidelines**: https://www.bing.com/webmasters/help/webmaster-guidelines-30fba23a

---

**Datum izrade izvještaja:** 2024  
**Verzija:** 1.0  
**Autorska prava:** Ovaj izvještaj je pripremljen za nelsonkb.com

---

*Za dodatna pitanja ili pomoć s implementacijom, kontaktirajte SEO stručnjake ili konsultirajte WordPress dokumentaciju.*

