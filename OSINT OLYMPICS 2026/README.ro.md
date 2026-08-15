[‹ Înapoi la toate exercițiile](../README.ro.md) · [English version →](README.md)

---

# Exercițiu Bonus: OSINT Olympics 2026

În acest exercițiu, având la dispoziție o fotografie, suntem rugați să determinăm data exactă la care aceasta a fost realizată.

<img width="714" height="513" alt="image" src="https://github.com/user-attachments/assets/1b6903fc-a5ef-4ff9-87db-32919cf7eeb1" />

# Rezolvare:

## Partea 1. Indicii și gânduri inițiale:

a. Se observă o construcție arcuită pe care este amplasat un panou. Pe acesta se distinge probabil numele companiei producătoare („MCH”), un text („KL.”) a cărui semnificație nu o cunoaștem încă, ora exactă și temperatura.

b. În spatele structurii se remarcă ceea ce pare a fi un salon de coafură, detaliu care ne va fi de folos la confirmarea geolocației.

c. Prezența zăpezii în jur indică faptul că, cel mai probabil, fotografia a fost realizată în lunile decembrie, ianuarie sau februarie.

d. Etichetele asociate imaginii (#sooooocold #winter #pandemic) pun un accent deosebit pe temperatura de -9 grade și ne oferă un indiciu esențial: #pandemic. Acest aspect sugerează că fotografia a fost făcută în una din cele 3 luni precizate anterior, în timpul unei pandemii.

## Partea 2. Investigare folosind motoare de căutare:

Deoarece nu deținem suficiente informații pentru o localizare imediată, primul pas a fost căutarea cuvintelor-cheie vizibile pe panou: „MCH” și „KL.”.

<img width="1496" height="1564" alt="image" src="https://github.com/user-attachments/assets/c2233679-e72e-4d3d-b59a-259d22c72558" />

După cum se poate observa, prima pagină de rezultate nu este foarte relevantă, oferind în principal locații din Malaezia (țară cu climat tropical). Totuși, explorând a doua pagină, am descoperit un rezultat promițător:

<img width="1348" height="296" alt="image" src="https://github.com/user-attachments/assets/06c43e33-fa6c-4dc4-b743-6356ec14bb13" />

[mch.dk](https://www.mch.dk) - Un website din Danemarca.

<img width="2530" height="1720" alt="image" src="https://github.com/user-attachments/assets/151ab463-6655-425c-9844-958dfeaf1c90" />

Nefiind evidentă o locație pe pagina principală, am accesat secțiunea de contact pentru a obține posibile adrese care să ne ajute la localizare.

<img width="1638" height="892" alt="image" src="https://github.com/user-attachments/assets/659d86e5-28e4-45e2-8d54-85b6affeaa23" />

## Partea 3. Investigare folosind Google Maps:

Adresa `Østergade 37 7400 Herning` a fost prima investigată, fiind repetată de două ori. Căutarea ne-a condus exact la ceea ce pare a fi locația din imagine, după cum se poate observa mai jos:

<img width="2390" height="1678" alt="image" src="https://github.com/user-attachments/assets/f616df76-4412-42d0-b910-a82ca7e77659" />
<img width="2530" height="1682" alt="image" src="https://github.com/user-attachments/assets/32b675b4-2dc4-4f42-916b-7fd1dd99fad6" />
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/b40c8f3a-168e-484c-adef-66a3855c06a6" />


Cu toate acestea, o primă discrepanță este faptul că fotografia de referință pare a fi mult mai veche comparativ cu imaginile actuale.

<img width="2310" height="1596" alt="image" src="https://github.com/user-attachments/assets/b93aaa68-99af-4959-b8e1-26a12836ed85" />

## Partea 4. Istoricul locației și date suplimentare:

Cea mai veche imagine disponibilă pe Google Street View datează din 2012. Un element care ridică suspiciuni este absența salonului de coafură în fundal. Prin urmare, trebuie să determinăm perioada de activitate a salonului (când a fost deschis, respectiv închis) pentru a restrânge intervalul de timp.

<img width="2534" height="1714" alt="image" src="https://github.com/user-attachments/assets/b8d2de98-b3e3-41f5-b0d8-f4543e6020ba" />

În perimetrul marcat cu roșu funcționa în trecut coaforul, în prezent acesta fiind un restaurant. Am notat adresa exactă, deoarece ne va fi necesară pentru a afla istoricul afacerii. Pentru o căutare eficientă, am folosit traducerea în daneză a cuvântului **coafor**.

<img width="1354" height="536" alt="image" src="https://github.com/user-attachments/assets/0eb203d8-82b7-4c22-ae0c-8708b0e655f9" />

Folosind aceste date (`Østergade 29, 7400 Herning`, `frisør`), am inițiat o nouă căutare pentru a afla perioada de activitate:

<img width="1964" height="1714" alt="image" src="https://github.com/user-attachments/assets/4fedfaae-e665-4932-9d04-b6e9a659b25a" />

Rezultatele indică faptul că salonul a fost deschis la data de 01.09.1990 și închis la 28.02.2010. Acest interval de timp este vast, însă eticheta #pandemic ne indică faptul că fotografia a fost realizată pe durata unei pandemii din acest interval.

<img width="1898" height="640" alt="image" src="https://github.com/user-attachments/assets/61211bd9-8b4f-4768-9889-291f7dcf90ae" />
<img width="1832" height="1532" alt="image" src="https://github.com/user-attachments/assets/346cae5c-a686-4316-ad78-4d74e92c3428" />

Din primul [rezultat](https://en.ssi.dk/news/epi-news/2010/no-1---2010), aflăm că perioada pandemiei a fost în 2009, iar numele virusului este A(H1N1). Astfel, am restrâns căutarea la anii 2009, respectiv 2010. Ținând cont de indiciile inițiale, ne putem concentra pe următoarele perioade: decembrie 2009, ianuarie 2010, februarie 2010, căutând temperatura exactă de -9 grade la ora 23:47.

## Partea 5. Analiza datelor meteo:

Pentru a obține aceste informații, putem folosi o căutare simplă: `Herning weather history`.

<img width="1856" height="548" alt="image" src="https://github.com/user-attachments/assets/ea67ae40-d21f-4303-ae61-8bacb7d2210b" />
<img width="2234" height="1190" alt="image" src="https://github.com/user-attachments/assets/dc21732c-8e45-434d-9ff7-7aae2d545a05" />

Site-ul accesat ne oferă un grafic util care elimină necesitatea de a verifica manual fiecare zi din decembrie 2009. După cum se observă subliniat, pe 31 decembrie s-a înregistrat o temperatură de -9 grade Celsius.

<img width="966" height="204" alt="image" src="https://github.com/user-attachments/assets/75c67b99-ab42-4a7e-bbab-2a1db5de57e7" />

Totuși, ne interesează temperatura exactă la ora 23:47, iar graficul ne arată clar că valoarea a fost diferită.
Verificând însă datele la 2 zile distanță, ajungem la următorul rezultat relevant:

<img width="1150" height="202" alt="image" src="https://github.com/user-attachments/assets/f2dd5f98-3c22-4209-847b-f365c5e8ed73" />

### Partea 6. Concluzie:

Coroborând toate datele obținute, putem confirma că fotografia a fost realizată la coordonatele aproximative `56°08'08.0"N 8°58'50.6"E`, pe data de **2 Ianuarie 2010**.
