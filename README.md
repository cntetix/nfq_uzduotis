##### Techninės detalės:
***
LocalStorage atmintis.
- Kiekvienas specialistas turi po savo atminties eilę, kuriose yra saugomi klientai(lankytojai).
- Taip pat kiekvienas specialistas turi išskyrtą atmintį, kuriose yra saugomos aptarnautų klientų laikas.
- Jau aptarnauti klientai yra saugomi "aptarnauti" atmintyje.

###### Specialisto puslapis.
- Rinkausi išskaidyti šį puslapį į keletą, nes lengviau naršyklėje naršyti tarp specialistų.
- Specialistų puslapius refreshinti nereikia, pati atmintis atsinaujina po kažkokių kitų puslapio veiksmų.
- Paspaudus migtuką automatiškai užfiksuojamas laikas kiek klientas praleido, tuo pačiu yra kviečiamas sekantis.

###### Švieslentės puslapis.
- Švieslentės puslapyje yra įdėtas keletas saugiklių
- PVZ: pasibaigus kliento eilei yra laukiama kol užsiregistruos nauji, tai eilei.

###### Admin puslapis.
**Paskaityti projekto paleidimą.**

###### Lankytojo puslapis.
- Klientui įvedus numerį, puslapis suranda kurioje eilėje/sąraše yra klientas ir poto apskaičiuojamas laikas pagal eilę.
- Jeigu nėra randomas nr., ieškoma ar toks nebuvo jau aptarnautas. Jeigu nebuvo - pranešama, kad tokio kliento nebuvo.

Naudota Bootstrap 4. 

## Projekto paleidimas:

Projektą pasileisti labai lengva - reikia atsidaryti index.html puslapį, kuriame yra migtukai į kitus puslapius.
Pradžioje rekomenduojama atsidaryti admin.html puslapį. Jame galima įkrauti >JSON failą, taip pat automatiškai yra sukuriami projektui būtini >localStorages lentelės.

<https://cntetix.github.io>

## Sprendimo pagrindimas:
 
 - Aš manau, kad šis būdas būtų labiausiai suprantamas kitiems developeriams. 
 - Kodas yra suskirstytas į gabaliukus, komentuotas, todėl kitiems būtų lengva skaityti.
 - Specialiai nesirinkau React'o, nes buvo liepta apsieiti be jų. Rinkausi level I ir level II, III nebespėjau.
