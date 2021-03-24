## Setup and test :

- clone this repository

- install : npm install

- dev : npm run dev - then open browser at http://localhost:1234

- build : npm run build - build files are in dist/ folder - source files are in src/ folder

## Original starting website url :

https://el-opcr.github.io/EricLonguemare_4_06032021/original/index.html

### Linters :

index page :

- [x] [HTML5](https://validator.w3.org/nu/?showsource=yes&showoutline=yes&showimagereport=yes&doc=https%3A%2F%2Fel-opcr.github.io%2FEricLonguemare_4_06032021%2Foriginal%2F)
- [x] [CSS3](https://jigsaw.w3.org/css-validator/validator?uri=https://el-opcr.github.io/EricLonguemare_4_06032021/original/&profile=css3svg&usermedium=all&warning=1&vextwarning=&lang=fr)
- [x] [Lighthouse report for mobile](https://lighthouse-dot-webdotdevsite.appspot.com//lh/html?url=https%3A%2F%2Fel-opcr.github.io%2FEricLonguemare_4_06032021%2Foriginal%2F)

page 2 :

- [x] [HTML5](https://validator.w3.org/nu/?showsource=yes&showoutline=yes&showimagereport=yes&doc=https%3A%2F%2Fel-opcr.github.io%2FEricLonguemare_4_06032021%2Foriginal%2Fpage2.html)
- [x] [CSS3](https://jigsaw.w3.org/css-validator/validator?uri=https://el-opcr.github.io/EricLonguemare_4_06032021/original/page2.html&profile=css3svg&usermedium=all&warning=1&vextwarning=&lang=fr)
- [x] [Lighthouse report for mobile](https://lighthouse-dot-webdotdevsite.appspot.com//lh/html?url=https%3A%2F%2Fel-opcr.github.io%2FEricLonguemare_4_06032021%2Foriginal%2Fpage2.html)

## Optimized website url :

https://el-opcr.github.io/EricLonguemare_4_06032021/dist/index.html

### Linters :

index page :

- [x] [HTML5](https://validator.w3.org/nu/?showsource=yes&showoutline=yes&showimagereport=yes&doc=https%3A%2F%2Fel-opcr.github.io%2FEricLonguemare_4_06032021%2Fdist%2F)
- [x] [CSS3](https://jigsaw.w3.org/css-validator/validator?uri=https://el-opcr.github.io/EricLonguemare_4_06032021/dist/&profile=css3svg&usermedium=all&warning=1&vextwarning=&lang=fr)
- [x] [Lighthouse report for mobile](https://lighthouse-dot-webdotdevsite.appspot.com//lh/html?url=https%3A%2F%2Fel-opcr.github.io%2FEricLonguemare_4_06032021%2Fdist%2Findex.html)

page 2 | Contact :

- [x] [HTML5](https://validator.w3.org/nu/?showsource=yes&showoutline=yes&showimagereport=yes&doc=https%3A%2F%2Fel-opcr.github.io%2FEricLonguemare_4_06032021%2Fdist%2Fcontact.html)
- [x] [CSS3](https://jigsaw.w3.org/css-validator/validator?uri=https://el-opcr.github.io/EricLonguemare_4_06032021/dist/contact.html&profile=css3svg&usermedium=all&warning=1&vextwarning=&lang=fr)
- [x] [Lighthouse report for mobile](https://lighthouse-dot-webdotdevsite.appspot.com//lh/html?url=https%3A%2F%2Fel-opcr.github.io%2FEricLonguemare_4_06032021%2Fdist%2Fcontact.html)

## SEO report :

| Catégorie                                               | Problème identifié                                                                       | Explication du problème                                                                              | Bonne pratique à adopter                                                 | Action recommandée                                                                                                   | Référence |
|---------------------------------------------------------|------------------------------------------------------------------------------------------|------------------------------------------------------------------------------------------------------|--------------------------------------------------------------------------|----------------------------------------------------------------------------------------------------------------------|-----------|
| Usage du site                                           | 404                                                                                      | Des liens sont en 404 – fichiers manquants – page contact cassée                                     | Pas de 404                                                               | Utiliser les bonnes urls                                                                                             |           |
| SEO – vitesse – core web vitals                         | Poids des images (BMP, taille, format ,,,)                                               | Le chargement des fichiers ralentit considérablement le chargement des pages,                        | Utiliser des formats adaptés et moderne (webp, retailler les images ,,,) | Conversion de toutes les images vers webp – Les redimensionner                                                       |           |
| SEO – Vitesse                                           | Un script est chargé mais non utilisé                                                    | Ne charger que ce qui est utile                                                                      | ,,,                                                                      | Retirer le script                                                                                                    |           |
| SEO – Vitesse                                           | minifier HTML, CSS et JS                                                                 | diminuer le poids des ressources à charger                                                           | ,,,                                                                      | Minifier HTML, CSS et JS                                                                                             |           |
| SEO – Vitesse                                           | Le chargement de tous les cripts peut-etre différé                                       | Charger les JS après le HTML ,,, (on lod)                                                            | ,,,                                                                      | Defer pour tous les JS                                                                                               |           |
| SEO – Lisibilité                                        | Balises alt des images non renseignées ou incohérentes                                   | Pas de lecture pour les lecteurs de contenu – SEO : identifié le contenu                             | Les ajouter                                                              | Alt significatives pour toutes les images                                                                            |           |
| SEO – Lisibilité                                        | Contraste insuffisant pour cerains bandeaux et boutons                                   | Lecture difficile                                                                                    | Contraste > 4,5 ou 3 pour les textes > 16px                              | Changer couleur et/ou taille de police                                                                               |           |
| SEO – Lisibilité                                        | Balise Head mal ordonnées                                                                | Liseuse incompléte ,,, Contenu moins significatif pour SEO ,,,                                       | Bon balisage des titres ,,,                                              | Le mettre en place (voir HTML linter W3c)                                                                            |           |
| SEO – mauvaises pratiques                               | Images utilisées à la place de texte                                                     | Le texte des images n’est pas indéxé, perte de sens pour les moteurs                                 | Utiliser du texte pour le rédactionnel                                   | Remplacer les images par le texte                                                                                    |           |
| SEO – Bourrage de mots clefs                            | Bourrage de mot clefs (keywords stuffing)                                                | Des mots clefs « pour le référencement » sont ajoutés au contenu HTML, mais cachés pour le visiteur, | Les retirer (et point ci’dessus)                                         | Retirer ces textes                                                                                                   |           |
| SEO – Liens sortants avec mots clefs                    | Annuaire « bidon »                                                                       | Des liens sont ajoutés en bas de page (échange ,,,) sans rapport avec le contenu                     | Ne pas faire de lien pour faire des liens                                | Retirer ces liens inutiles                                                                                           |           |
| Lisibilité                                              | Balisage formulaire incorrect                                                            | La navigation au clavier ‘tab) n’est pas possible – On attend un mail à la place de texte ,,,        | Balisage correct                                                         | Mis en place le bon balisage                                                                                         |           |
| Wording – SEO – Meta                                    | Mauvais ou pas en place                                                                  | Donner du sens et le marquer                                                                         | Meta desc significative – Lien avec sens ,,,                             | Mise en place et/ou complétion,                                                                                      |           |
| SEO – Sécurité, bonnes pratiques, respect des visiteurs | Des librairies/framework dépassés et présentatnt des failles de sécurité sont utilisées, | XSS ,,, non corrigées ,,, mauvaise pratique                                                          | Les mettre à jour                                                        | Pas fait – trop de changement – Boostrap et Jquery – A faire : Jquery 3,5,1 ou 3,6 – ou Boostrap 5beta et Vanilla JS |           |

[Download SEO Report](https://github.com/el-opcr/EricLonguemare_4_06032021/raw/master/SEO_Report/Audit-SEO.xlsx)

## SEO sources :

- [Seroundtable](https://www.seroundtable.com/) - Followed on a regular basis since 2001
- [Searchengineland](https://searchengineland.com/) - Followed on a regular basis since about 10 years
- [Webmasterworld](https://www.webmasterworld.com/) - Followed on a regular basis since 1998
- [Webrankinfo](https://www.webrankinfo.com/) - Followed on a regular basis since 2003

And a lot of others (SEMRUSH, developers.google.com/web, schema.org, Google Search Console, Bing webmaster tools, Yandex
webmaster tool, Google Analytics, Matomo ... )

