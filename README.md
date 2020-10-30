# PRA 1 - Web Scraping
Repositori amb els arxius creats i obtinguts durant la pràctica 1

(PROVISIONAL)

Autors: Albert Gil Devesa i Aleix Borrella Colomé

Idea i objectiu: Obtenir TOTS els productes que apareixen en el supermercat online BONPREU classificats per categoria i subcategories, amb informació del nom del producte, del seu preu, de la quantitat, així com del preu unitari per a futures aplicacions com la comparació dels preus d'altres supermercats (per exemple).

Instruccions: Per aconseguir-ho, hem implementat 2 codis, en primer lloc el urls.py que navega per a cada una de les categories i subcategories i n'obté la url, generant un llistat d'aproximadament 1000 urls diferents sobre les cals caldrà extreure la informació. En segon lloc, hem implementat el codi scraper.py en el qual es fa el web scraping de la informació dels productes a partir de les urls proporcionades pel codi anterior. Com a resultat, totes les dades són escrites i exportades a un fitxer .csv, que conté la informació d'aproximadament 10.000 productes (bp_dataset.csv).
