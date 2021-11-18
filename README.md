Meningsmålinger til kommunalvalget
---

### Beskrivelse

En samling af meningsmålinger til kommunalvalget 2021. 

### Indhold

Filen `kvpolls.csv` indeholder data fra de respektive meningsmålinger der er lavet i de forskellige kommuner. Da der er forskel på, hvilke partier der stiller op i de forskellige kommuner, har datasættet et format, hvor hver række er ét estimat for et parti i en meningsmåling. Konkret er der de følgende informationer for hvert estimat:

 - `kommune` = Navn på kommunnen
 - `institut` = Navn på instituttet der gennemfører meningsmålingen
 - `parti` = Navn på partiet
 - `opbakning` = Opbakning til partiet i meningsmålingen (i %)
 - `n` = Stikprøvestørrelsen
 - `dato` = Data for hvornår dataindsamlingen sluttede (i ISO 8601 format, `YYYY-MM-DD`)
 - `valg_2017` = Opbakning til partiet ved kommunalvalget i 2017
 - `valgvindsprognose_2021` = Opbakning til partiet i [Valgvindsprognose 2021](https://www.mm.dk/artikel/ny-model-spaar-vaelgernes-kryds-i-alle-kommuner)
 