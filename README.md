## Detyra ne pritje
 - Ruajtja / shperndarja e ambalazhit
 - Asetet
 - Kosto shtese per mallin ne blerje


## Detyra ne zhvillim 
 - Raporti i gjendjes se magazines
 - Te zonat nuk shfaqen klientet (API - ok), te perdoruesi kur i eshte caktuar 1/me shume zona nuk shfaqen te shtimi / edit i klientit
 - Kartela e produktit
 - Totali i shitjeve

===
## **30.06.2022**
 - Integrity tests / code review / refactor / bug fixing ne modulet 
  1. Kompanitë
  2. Magazinat
  3. Arkat
  4. Nivelet e Çmimeve
  5. Produktet / Kategoritë
  6. Furnizimet

## **29.06.2022**
 - Pagination dinamik te produktet, klientet dhe faqet nderlidhese
 - Permiresim i strukturave ruajtese ne bazen e te dhenave
 - Pershpejtim i sistemit te seleksionimit te te dhenave dhe rritja e eficences se kerkimit ne db
 - Teste integriteti
## **28.06.2022**
### Shitjet
Perllogaritja e totalit te faturave behet vetem per rekordet qe jane shfaqur ne ate faqe.

### Furnizimet
Perfundoi opsioni i ngarkimit nga nje dokument excel

### Te tjera
Jane pershpejtuar disa faqe (Shitjet, Produktet, Produktet sipas Magazines), pagination kerkon vetem sasine e produkteve qe perdoruesi pret te shohe ne faqe.
Eshte shtuar opsioni qe nje kompani mund te mos lejoje balance negative ne magazine.
U rregullua glitch qe shkaktonte logout


## **27.06.2022**
### Furnizimet
Ne modulin e furnizimeve u rregullua funksionaliteti `Modifiko furnizim`.
Eshte shtuar opsioni i shtimit te `TVSH` se produktit.
Nese perdoruesi nuk shenon ndarjen e TVSH, atehere sistemi gjeneron me TVSH baze te atij produkti.

### Shitjet
- U permiresua struktura e ruajtjes se shitjeve, listimi i tyre eshte me i shpejte tani.
-  Klienti i rastit del i zgjedhur by default te bar / invoice
 - Vlera e TVSH te dritarja e fatures u rregullua
 - Pershpejtuar gjenerimi i fatures pas shitjes
 - U regullua problemi i ruajtjes se opsioneve kur perdoruesi ben logout / login
 - Fshirja ne grup e faturave u perfundua

### Kreu
Jane shtuar **3** indikatore te rinj te kreu, 

 1. TVSH e Blerjes
 2. TVSH per tu paguar
 3. Kosto e furnizimeve


