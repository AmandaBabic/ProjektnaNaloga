# Projektna naloga: Analiziranje višine, teže in ITM vrednosti po svetu

Avtor: Amanda Babič 

Moja projektna naloga pri predmetu UVP, program Finančna matematika, študijsko leto 2022/23, zajema dva dela: zajemanje podatkov in analizo podatkov o višini, teži in indeksu telesne mase (ITM) moških in žensk po svetu. Zanjo sem uporabila programski jezik Python, s pomočjo katerega sem s spletne strani [WorldData](https://www.worlddata.info/average-bodyheight.php) vzela podatke o višini, teži in ITM vrednosti moških in žensk glede na države in dele kontinentov po svetu. ITM vrednost nam lahko veliko pove, zato sem kasneje enako naredila s spletno stranjo [BMI Calculator](https://www.calculator.net/bmi-calculator.html), iz katere sem črpala klasifikacijo indeksa telesne mase.

Podatke sem nato uredila v .csv datoteke, jih obdelala v Jupyter-u s knjižnico Pandas za Python in shranila v mapo *obdelani podatki*. Datoteke so sledeče:
- *drzave.csv*: Združen csv (*podatkiM.csv* in *podatkiZ.csv*) - podatki obeh spolov o višini, teži in ITM vrednosti glede na države 
- *kontinenti.csv*: Podatki o višini in teži moških in žensk glede na dele kontinentov
- *podatkiM.csv*: Podatki o višini moških, teži moških in ITM vrednosti moških glede na države
- *podatkiZ.csv*: Podatki o višini žensk, teži žensk in ITM vrednosti žensk glede na države
- *dodatno.csv*: Podatki o klasifikaciji vrednosti ITM in ITM prime

Potek analiz poteka v naslednjem vrstnem redu: 
- AnaliziranjePodatkov_visina
- AnaliziranjePodatkov_teza
- AnaliziranjePodatkov_ITM
- AnaliziranjePodatkov_ITM_klasifikacija


## Navodila za uporabo
Tako za zajem podatkov kot za analizo sem uporabljala jupyter notebooks, prav so mi prišli tudi razni paketi. Pri obdelavi podatkov sem se oprla na *csv*, *os*, *requests* in *re*, pri analizi pa *pandas*, *os*, *matplotlib*, *numpy* in *matplotlib.pyplot*.
