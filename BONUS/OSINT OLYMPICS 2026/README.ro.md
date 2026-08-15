[‹ Înapoi la toate exercițiile](../README.ro.md) · [English version →](README.md)

---

# Exercițiu Bonus: OSINT Olympics 2026

În acest exercițiu, având la dispoziție o fotografie, suntem rugați să determinăm data exactă la care aceasta a fost realizată.

![alt text](Pasted_image_20260816002907.png)

# Rezolvare:

## Partea 1. Indicii și gânduri inițiale:

a. Se observă o construcție arcuită pe care este amplasat un panou. Pe acesta se distinge probabil numele companiei producătoare („MCH”), un text („KL.”) a cărui semnificație nu o cunoaștem încă, ora exactă și temperatura.

b. În spatele structurii se remarcă ceea ce pare a fi un salon de coafură, detaliu care ne va fi de folos la confirmarea geolocației.

c. Prezența zăpezii în jur indică faptul că, cel mai probabil, fotografia a fost realizată în lunile decembrie, ianuarie sau februarie.

d. Etichetele asociate imaginii (#sooooocold #winter #pandemic) pun un accent deosebit pe temperatura de -9 grade și ne oferă un indiciu esențial: #pandemic. Acest aspect sugerează că fotografia a fost făcută în una din cele 3 luni precizate anterior, în timpul unei pandemii.

## Partea 2. Investigare folosind motoare de căutare:

Deoarece nu deținem suficiente informații pentru o localizare imediată, primul pas a fost căutarea cuvintelor-cheie vizibile pe panou: „MCH” și „KL.”.

![alt text](Pasted_image_20260816003958.png)

După cum se poate observa, prima pagină de rezultate nu este foarte relevantă, oferind în principal locații din Malaezia (țară cu climat tropical). Totuși, explorând a doua pagină, am descoperit un rezultat promițător:

![alt text](Pasted_image_20260816004228.png)

[mch.dk](https://www.mch.dk) - Un website din Danemarca.

![alt text](Pasted_image_20260816004533.png)

Nefiind evidentă o locație pe pagina principală, am accesat secțiunea de contact pentru a obține posibile adrese care să ne ajute la localizare.

![alt text](Pasted_image_20260816004759.png)

## Partea 3. Investigare folosind Google Maps:

Adresa `Østergade 37 7400 Herning` a fost prima investigată, fiind repetată de două ori. Căutarea ne-a condus exact la ceea ce pare a fi locația din imagine, după cum se poate observa mai jos:

![alt text](Pasted_image_20260816004946.png)
![alt text](Pasted_image_20260816005716.png)
![alt text](Pasted_image_20260816005756.png)

Cu toate acestea, o primă discrepanță este faptul că fotografia de referință pare a fi mult mai veche comparativ cu imaginile actuale.

![alt text](Pasted_image_20260816010056.png)

## Partea 4. Istoricul locației și date suplimentare:

Cea mai veche imagine disponibilă pe Google Street View datează din 2012. Un element care ridică suspiciuni este absența salonului de coafură în fundal. Prin urmare, trebuie să determinăm perioada de activitate a salonului (când a fost deschis, respectiv închis) pentru a restrânge intervalul de timp.

![alt text](Pasted_image_20260816010929.png)

În perimetrul marcat cu roșu funcționa în trecut coaforul, în prezent acesta fiind un restaurant. Am notat adresa exactă, deoarece ne va fi necesară pentru a afla istoricul afacerii. Pentru o căutare eficientă, am folosit traducerea în daneză a cuvântului **coafor**.

![alt text](Pasted_image_20260816011132.png)

Folosind aceste date (`Østergade 29, 7400 Herning`, `frisør`), am inițiat o nouă căutare pentru a afla perioada de activitate:

![alt text](Pasted_image_20260816011955.png)

Rezultatele indică faptul că salonul a fost deschis la data de 01.09.1990 și închis la 28.02.2010. Acest interval de timp este vast, însă eticheta #pandemic ne indică faptul că fotografia a fost realizată pe durata unei pandemii din acest interval.

![alt text](Pasted_image_20260816012347.png)
![alt text](Pasted_image_20260816012606.png)

Din primul [rezultat](https://en.ssi.dk/news/epi-news/2010/no-1---2010), aflăm că perioada pandemiei a fost în 2009, iar numele virusului este A(H1N1). Astfel, am restrâns căutarea la anii 2009, respectiv 2010. Ținând cont de indiciile inițiale, ne putem concentra pe următoarele perioade: decembrie 2009, ianuarie 2010, februarie 2010, căutând temperatura exactă de -9 grade la ora 23:47.

## Partea 5. Analiza datelor meteo:

Pentru a obține aceste informații, putem folosi o căutare simplă: `Herning weather history`.

![alt text](Pasted_image_20260816013607.png)
![alt text](Pasted_image_20260816013731.png)

Site-ul accesat ne oferă un grafic util care elimină necesitatea de a verifica manual fiecare zi din decembrie 2009. După cum se observă subliniat, pe 31 decembrie s-a înregistrat o temperatură de -9 grade Celsius.

![alt text](Pasted_image_20260816013926.png)

Totuși, ne interesează temperatura exactă la ora 23:47, iar graficul ne arată clar că valoarea a fost diferită.
Verificând însă datele la 2 zile distanță, ajungem la următorul rezultat relevant:

![alt text](Pasted_image_20260816014106.png)

### Partea 6. Concluzie:

Coroborând toate datele obținute, putem confirma că fotografia a fost realizată la coordonatele aproximative `56°08'08.0"N 8°58'50.6"E`, pe data de **2 Ianuarie 2010**.
