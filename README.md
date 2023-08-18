# Projektna naloga: Analiziranje višine, teže in ITM vrednosti po svetu

Avtor: Amanda Babič
Predmet: UVP
Finančna matematika
2022/2023

Moja projektna naloga pri predmetu UVP zajema dva dela: zajemanje podatkov in analizo podatkov o višini, teži in indeksu telesne mase (ITM) moških in žensk po svetu. Zanjo sem uporabila programski jezik Python, s pomočjo katerega sem s spletne strani [WorldData](https://www.worlddata.info/average-bodyheight.php) vzela podatke o višini, teži in ITM vrednosti moških in žensk glede na države in dele kontinentov po svetu. ITM vrednost nam lahko veliko pove, zato sem kasneje enako naredila s spletno stranjo [BMI Calculator](https://www.calculator.net/bmi-calculator.html), iz katere sem črpala klasifikacijo indeksa telesne mase.

Podatke sem nato uredila v .csv datoteke, jih obdelala v Jupyter-u s knjižnico Pandas za Python in shranila v mapo *obdelani podatki*. Datoteke so sledeče:
- *drzave.csv*
- *kontinenti.csv*
- *podatkiM.csv*
- *podatkiZ.csv*
- *dodatno.csv*

Tako za zajem podatkov kot za analizo sem uporabila jupyter notebooks.
