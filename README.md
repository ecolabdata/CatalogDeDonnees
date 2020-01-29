# Catalogue de données MTES/MCTRCT

Il est important de recenser les données gérées par les acteurs,
d'une part afin de pouvoir les exploiter pour répondre à de nouveaux besoins,
et d'autre part afin de respecter les obligations légales de transparence de l'administration
([L'accès aux documents administratifs et la réutilisation des informations publiques, livre III du
CRPA](https://www.legifrance.gouv.fr/affichCode.do?idSectionTA=LEGISCTA000031367685&cidTexte=LEGITEXT000031366350))
et d'information de tous sur l'environnement
([Droit d'accès à l'information relative à l'environnement, livre Ier, titre II, chapitre IV du code de l'environnement](https://www.legifrance.gouv.fr/affichCodeArticle.do?cidTexte=LEGITEXT000006074220&idArticle=LEGIARTI000033140333&dateTexte=20200129)).

Dans un souci d'efficacité il est indispensable de standardiser la description de ces données au travers de métadonnées
et d'organiser la gestion de ces métadonnées dans des catalogues.

Le W3C a publié un standard ([DCATv2](https://www.w3.org/TR/vocab-dcat-2/))
qui définit un vocabulaire de données liées (RDF)
pour faciliter l'interopérabilité entre catalogues de données.
La commission européenne a défini de son côté
un [profil DCAT-APv2](https://joinup.ec.europa.eu/solution/dcat-application-profile-data-portals-europe/releases)
s'appuyant sur DCATv2.
ainsi qu'une [extension de DCAT-AP pour les données géographiques,
appelée GeoDCAT-AP](https://semiceu.github.io/GeoDCAT-AP/releases/1.0.1/geodcat-ap_1.0.1.pdf),
et une [autre pour les données statistiques, appelée statDCAT-AP](https://joinup.ec.europa.eu/release/statdcat-ap/101).

Par ailleurs le W3C a publié un standard ([JSON-LDv1.1](https://www.w3.org/TR/json-ld11/)) pour publier
des données liées en JSON comme micro-données.

Enfin, il est de la responsabilité de la SGD du MTES/MCTRCT de définir des règles sur la gestion des données.
Dans ce cadre, il est donc proposé que chaque détenteur de données constitue un ou des catalogues de données
respectant le standard DVCATv2 et s'appuyant dans la mesure du possible sur le profil DCAT-APv2
et ses 2 extensions citées ci-dessus.
Ces catalogues pourront être répartis sur les différentes sites applicatifs dans lesquels des données sont gérées
et seront exposées sous la forme de micro-données JSON-LD.  

Le SGD mettra en place avec l'appui du SNUM un outil de cataloguage qui recensera les URL des différents sites applicatifs
et ira moissonner les différents catalogues pour les exposer de manière ergonomique aux utilisateurs
et pousser les métadonnées sur différents catalogues comme data.gouv.fr.
