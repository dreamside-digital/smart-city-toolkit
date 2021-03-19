---
layout: default
title: Data Governance
permalink: /municipal-administration/data-governance
---

# Gouvernance des Données

## Services : Gouvernance des données

La gouvernance des données est une préoccupation pour toutes les organisations faisant un usage intensif de données, y compris les administrations municipales. Un système de gouvernance des données efficace doit tenir compte des exigences divergentes des parties prenantes et de nombreuses considérations juridiques, financières et éthiques, qui ne seront pas toutes connues au moment de sa conception. Un système de gouvernance des données doit permettre de trouver un juste équilibre entre les priorités concurrentes toute en offrant la souplesse nécessaire pour s’adapter aux nouveaux enjeux.

La valeur des données a grimpé en flèche ces dernières années, leur contribution à l’innovation et à la prestation de services étant de plus en plus évidente. Diverses organisations et entités manifestent un intérêt croissant pour l’accès aux données gérées par les administrations municipales. Les modèles traditionnels de gestion des données des municipalités ne mettent pas l’accent sur le partage des données, mais sur la protection des intérêts privés qui s’y rattachent, et ce, même quand certaines personnes concernées auraient bénéficié d’un partage plus permissif des données et auraient consenti à un tel partage. En conséquence, les administrations municipales ont commencé à explorer des modèles de gestion des données qui leur permettent de partager des données avec l’industrie et les utilisateurs d’intérêt public dans le respect de leurs obligations et des lois.

### Applications et solutions : La fiducie de données

Le concept de « fiducie de données » suscite beaucoup d’intérêt chez ceux qui étudient et tentent de résoudre les problèmes de gouvernance des données. Ces fiducies sont des structures organisationnelles conçues pour gérer des données \(notamment leur utilisation et leurs modalités d’accès\) conformément aux principes de common law. Le contenu de la fiducie \(les données\) doit être géré par des administrateurs \(les fiduciaires\) dans l’intérêt des bénéficiaires de la fiducie. En pratique, le concept de fiducie de données est fluide, et plusieurs structures organisationnelles se désignent elles-mêmes comme telles. Généralement, une « vraie » fiducie de données possède deux caractéristiques principales : l’adhésion au principe de gestion des actifs par un fiduciaire dans l’intérêt des bénéficiaires et une responsabilité de type fiduciaire envers les bénéficiaires afin que les conditions de la fiducie puissent être appliquées. En pratique, cependant, de nombreux véhicules de gouvernance des données appelés « fiducies de données » ne présentent aucune de ces caractéristiques.

Les fiducies de données ne représentent qu’un des nombreux systèmes émergents de gouvernance des données, qui englobent aussi les données ouvertes, les bases de données communes, le groupage des données et les coopératives de données.

### Technologies

**Cryptographie** – L’accès aux données doit être réservé aux entités autorisées et les solutions cryptographiques sont un moyen de s’en assurer. Le cryptage des données stockées et en cours de transmission garantit que seules les entités autorisées peuvent accéder aux données.

**Chaîne de blocs** – Le projet DECODE de Barcelone est l’une des applications de gouvernance des données les plus intéressantes des dernières années.

**DECODE** \(acronyme anglais pour « écosystème décentralisé de données appartenant aux citoyens »\) utilise des technologies de cryptage et de chaîne de blocs pour donner aux habitants des villes un plus grand contrôle sur leurs données. Les citoyens peuvent préciser le degré de confidentialité qu’ils souhaitent avoir pour les données recueillies par les appareils municipaux et compteurs intelligents. Les données sont recueillies en fonction de ces préférences, et leur stockage et traitement dans une chaîne de blocs est gage de transparence et de vérifiabilité.

### Gestion des risques susceptibles d’engager la responsabilité

| Vie privée |
| :--- |
| **Risques** |
| ⚠ La gouvernance des données implique généralement l’intendance des renseignements personnels. |
| :warning: La gouvernance municipale implique généralement l’intendance des données des citoyens. Si ces données peuvent être associées ou réassociées à des personnes identifiables, il en résulte des obligations de respect de la vie privée. |
| ⚠ Les défis en matière de gouvernance des données ne sont pas tous liés à la protection de la vie privée. Les données environnementales publiques, par exemple, sont peu susceptibles d’être associées à des particuliers. En revanche, l’un des défis qui se posent dans la gestion des données générées par les applications de ville intelligente est l’« identifiabilité » des données associées aux personnes, même lorsqu’elles sont en apparence anonymes.  C’est notamment le cas lorsque des données géographiques permettent contre toute attente d’identifier des personnes. |
| ⚠  Les fiducies de données sont particulièrement susceptibles de soulever des enjeux relatifs à la vie privée.  Souvent, des modèles d’intendance de type fiduciaire sont proposés pour surmonter les difficultés liées à l’obtention du consentement à la collecte de données pouvant contenir des renseignements personnels.  Les données recueillies dans les espaces publics peuvent très bien comporter des renseignements personnels issus des déplacements et de l’activité des personnes à ces endroits.  Le recours aux fiducies a donc été proposé comme solution au défi d’obtenir le consentement de ces personnes. |
| **Gestion des risques** |
| ✅ Les structures de gouvernance des données doivent considérer le respect de la vie privée comme un élément essentiel de toute intendance responsable. |
| ✅  Anonymisez les données.  Faites des stratégies d’anonymisation une norme pour le partage de renseignements sans consentement. Si des renseignements personnels doivent absolument être recueillis, anonymisez-les dès que possible. |
| ✅ Recueillez les données de manière impersonnelle.  Lorsque les objectifs de gouvernance des données ne nécessitent pas de renseignements personnels, n’en recueillez pas. |
| ✅  Floutez les données. Utilisez des techniques de floutage des données pour en préserver la confidentialité. Par exemple, n’incluez pas les points de départ et d’arrivée dans les données sur les itinéraires, de sorte qu’on ne puisse pas relier l’itinéraire à la personne qui l’a parcouru. Flouter les données de secteurs sensibles renforce la sécurité des renseignements personnels. |
| ✅ Anonymisez à la source. De nombreuses technologies de collecte permettent de recueillir des données moins détaillées. |
| ✅ Assurez-vous que vos partenaires et entrepreneurs respectent les restrictions en matière de collecte. Si vous achetez des données à une société privée, vérifiez qu’elle respecte ses obligations en matière de respect de la vie privée prévues par les lois applicables. |
| ✅ Suivez les [pratiques exemplaires en matière de protection de la vie privée](../metapreoccupations/vie-privee.md). |

| Sécurité |
| :--- |
| **Risques** |
| ⚠  La gouvernance des données est étroitement liée à leur sécurité.  En effet, le contrôle de l’accès est un aspect essentiel de la gouvernance des données. |
| **Gestion des risques** |
| ✅  Les outils et stratégies de cryptage protègent les données stockées et en cours de transmission tout en sécurisant les droits d’accès aux données sous intendance. |
| :heavy\_check\_mark: Bon nombre des solutions aux risques pour la vie privée atténueront aussi les risques pour la sécurité, par exemple l’anonymisation à la source, sinon l’anonymisation dès que possible.  Si des renseignements personnels sont recueillis, ils doivent être conservés dans un endroit sûr. |
| ✅ Suivez les [pratiques exemplaires en matière de sécurité](../metapreoccupations/securite.md). |

| Propriété intellectuelle |
| :--- |
| **Risques** |
| ⚠ La gouvernance des données peut inclure la gestion de l’accès et du partage pour les données assujetties à des droits de propriété intellectuelle, par exemple des droits d’auteur ou des droits à la confidentialité. |
| **Gestion des risques** |
| ✅  Les accords de confidentialité comportent souvent des renseignements cruciaux sur les conditions d’accès, notamment : a\) la durée d’utilisation \(qui suppose une date d’expiration\); b\) l’identité des personnes qui peuvent accéder à l’information; c\) les usages autorisés; et d\) les conditions de stockage \(par exemple, il peut être exigé que les données soient cryptées et ne soient pas dupliquées\). |
| ✅  Les licences pour les compilations originales de données protégées par le droit d’auteur peuvent comporter des conditions d’accès, notamment des durées d’utilisation, des utilisations autorisées et d’autres restrictions. |
| ✅  Examinez attentivement les [risques liés à la propriété intellectuelle](../metapreoccupations/propriete-intellectuelle.md). |

| Inclusion |
| :--- |
| **Risques** |
| ⚠  La gouvernance des données demande une intendance réfléchie : les flux de données sont gérés, mais à quelle fin, au profit de qui? |
| ✅  Les municipalités qui s’engagent dans la voie des villes intelligentes doivent s’assurer que tous les citoyens en profitent. |
| ✅  Elles doivent aussi apprendre à faire prévaloir les intérêts des citoyens sur les intérêts particuliers.  Par exemple, même s’il ne fait aucun doute que les consommateurs bénéficient de la recherche et de l’innovation du secteur privé, les citoyens n’accepteraient pas nécessairement de communiquer leurs données pour servir des intérêts commerciaux. |
| **Gestion des risques** |
| ✅  Les structures d’intendance des données de type fiduciaire devraient avoir un modèle de fiducie bien défini.  Ce modèle devrait permettre au fiduciaire d’identifier les bénéficiaires des données et de prendre des décisions d’accès et d’exploitation d’après une évaluation de bonne foi de l’intérêt des bénéficiaires. |
| ✅  Les forums multipartites ne sont pas bien adaptés pour agir comme fiduciaires dans de telles structures car, par définition, leurs représentants ont des allégeances divergentes.  Ces forums peuvent néanmoins aider les fiduciaires à prendre des décisions éclairées. |
| ✅  [Suivez les pratiques exemplaires en matière d’inclusivité](../metapreoccupations/inclusion.md). |

### Ressources

Alanus von Radecki, Grainne Bradley et Martine Tommis, [« Management & Governance of Urban Data Thematic Report »](https://urbact.eu/sites/default/files/media/tr_urbandata_v1.0_may2018_3.pdf), Urbact, mai 2018 – \*Ce rapport résume les résultats d’une réunion du réseau européen SmartImpact visant à déterminer comment les villes peuvent utiliser les données pour fournir de meilleurs services, assurer leur durabilité et développer l’économie locale. Le rapport est destiné aux fonctionnaires municipaux et aux décideurs politiques qui souhaitent améliorer leur gouvernance des données. Il utilise des exemples réels de façons dont les villes peuvent gérer les données dans l’intérêt des citoyens sans compromettre d’éventuelles occasions d’affaires.

[« Building Ontario’s Next Generation Smart Cities through Data Governance: Part 2: Towards a Smart City Data Trust »](https://www.orion.on.ca/wp-content/uploads/2019/11/Smart-Cities_MaRS_Towards-a-Smart-City-Data-Trust.pdf), ORION, 5 novembre 2019 – \*Tiré d’une série de rapports produits par Calcul Ontario, ORION et MaRS Discovery District d’après des modèles de recherche sur la gouvernance des données pour les villes intelligentes. Ce rapport traite des choix concrets de conception d’une fiducie de données pour ville intelligente et fournit des recommandations préliminaires visant à assurer le bon fonctionnement d’une telle fiducie. Le rapport situe la recherche dans le domaine de la mobilité personnelle \(le transport\), puisque celle-ci implique l’utilisation de renseignements commerciaux et personnels sensibles et nécessite un mécanisme de gouvernance des données.

[« Building Ontario’s Next Generation Smart Cities through Data Governance: Part 4: The Future of Ontario’s Data »](https://computeontario.ca/wp-content/uploads/2019/11/Smart-Cities_The-future-of-Ontario%E2%80%99s-data-1.pdf), ORION, 5 novembre 2019 – \*Ce rapport résume les conclusions du projet de Calcul Ontario et ORION sur les villes intelligentes sous l’angle de la gouvernance des données. Il présente différents modèles de gouvernance des données répondant aux exigences en matière de partage et de protection des données, dans un continuum sur le plan du contrôle, de la légalité, de la réglementation et de la complexité. Ces modèles comprennent des principes, des espaces communs de données, des collectifs de données et des fiducies de données, classés du plus faible degré de contrôle et de complexité au plus élevé. Les caractéristiques, avantages et inconvénients, ainsi que des exemples de chaque modèle sont présentés brièvement; le reste du rapport est consacré aux fiducies de données et à leur application dans des projets pilotes mettant en jeu des données sur la santé et la mobilité et une architecture ouverte.

Copenhagen Solutions Lab, [« City Data Exchange – Lessons learned from a public/private data collaboration »](https://cphsolutionslab.dk/content/2-what-we-do/3-data-platforms/3-city-data-exchange/1-learnings-from-the-city-data-exchange-project/city-data-exchange-cde-lessons-learned-from-a-public-private-data-collaboration.pdf?1527149474), mars 2018 – \*Ce rapport préparé par la municipalité de Copenhague présente les leçons tirées du projet City Data Exchange \(CDE\), une plateforme de partage de données qui a permis à des organisations publiques et privées d’échanger des données. Cette initiative novatrice visait à tester la capacité du marché à fournir de nouvelles solutions de partage de données. Le rapport présente les principaux résultats et défis du CDE et contient des recommandations pour améliorer le partage des données. Les trois principales pistes pour créer une infrastructure de données efficace sont intéressantes. Premièrement, le rapport recommande d’établir des cas d’utilisation efficace des données pour relever des défis ou saisir des occasions spécifiques. Deuxièmement, il préconise la création d’une communauté de données régionale ou nationale pour favoriser les débouchés. Troisièmement, le rapport suggère d’établir des normes communes pour le partage des données. Ces recommandations générales, issues d’un projet réel, peuvent aider les villes qui s’intéressent aussi aux plateformes de partage de données.

[« Designing a Data Collaborative »](https://datacollaboratives.org/canvas.html) – \*\*Le Data Collaboratives Guide présente les huit phases de conception et de mise en œuvre d’un collectif de données, étayées par des exemples et des ressources pour améliorer les résultats. Cette publication du GovLab se veut une ressource pour créer de la valeur publique par l’échange de données.

Center for Government Excellence, [« First Things First: Laying the foundation for a Smart City »](https://govex.jhu.edu/wp-content/uploads/2018/05/SMARTCITIES_GUIDE_FINAL-1.pdf), mai 2018 – \*Fruit d’une collaboration entre l’Université du Maryland, l’Université d’État Morgan, l’Université de Baltimore et le Center for Government Excellence de l’Université John Hopkins, ce guide offre un aperçu des aspects clés de la planification et de la mise en œuvre des données de ville intelligente. Le guide présente les mesures nécessaires à la mise en place de bonnes pratiques de gestion et d’utilisation des données et cite d’autres ressources sur les structures et les grandes étapes de la gouvernance des données.

Geoff Mulgan et Vincent Straub, [« The new ecosystem of trust »](https://www.nesta.org.uk/blog/new-ecosystem-trust/) Nesta \(21 février 2019\) – \*Ce document résume l’état actuel de la gouvernance des données et suggère la création d’un nouveau groupe de solutions sous forme de fiducies de données afin d’offrir un meilleur contrôle aux citoyens et une plus grande valeur au public. Le document fait un tour d’horizon de la gouvernance des données et illustre le niveau de contrôle ou de choix des gens relativement aux méthodes de partage des données. Mulgan et Straub proposent un nouveau cadre de gouvernance des données axé sur les fiducies de données qui comportent un élément de nature publique, notamment des données publiques, des données principalement d’intérêt public et des données publiques-privées.

Jack Hardinges et coll., [« Data trusts: lessons from three pilots »](https://docs.google.com/document/d/118RqyUAWP3WIyyCO4iLUT3oOobnYJGibEhspr2v87jg/edit), Open Data Institute, avril 2019 – \*Ce rapport de l’ODI se base sur les recherches menées dans le cadre de trois projets pilotes pour expliquer les fiducies de données, proposer un cycle de vie potentiel pour ces fiducies et proposer des recommandations aux gouvernements et autres entités qui souhaitent mettre en œuvre ou utiliser des données. Le rapport prône l’utilisation de fiducies dans les infrastructures de données et résume les leçons tirées des projets pilotes. Son modèle de cycle de vie est un guide général pour aborder les fiducies de données, à la condition de les concevoir individuellement en fonction du contexte. Il comprend six phases, toutes détaillées dans le rapport et assorties d’activités à entreprendre et de thèmes clés.

PwC, [« The foundation for smart city success: Seven layers of data governance and management »](https://www.pwc.com/us/en/industries/capital-projects-infrastructure/library/assets/pwc-foundation-of-smart-cities.pdf) – \*Le rapport de PricewaterhouseCoopers \(PwC\) propose sept couches de base de gestion de la gouvernance des données pour des villes intelligentes réussies. Se fondant sur un examen des meilleures pratiques mondiales et une analyse indépendante, PwC affirme que les sept couches \(catégories, consentement, collecte, anonymisation, stockage, accès et monétisation\) créent une base pour des données sûres et exploitables.

Theresa Scassa, Merlynda Vilain, [Governing Smart Data in the Public Interest: Lessons from Ontario’s Smart Metering Entity CIGI Paper No. 221](https://www.cigionline.org/publications/governing-smart-data-public-interest-lessons-ontarios-smart-metering-entity), \(2019\) - Ce document se concentre sur la gouvernance des données saisies par le biais de “technologies intelligentes” et utilise le programme de compteurs intelligents de l’Ontario comme étude de cas.

GeoConnections, [Geospatial Data Preservation Primer](https://doi.org/10.4095/296299), \(2015\) - Une introduction à l’archivage et à la préservation des données géospatiales numériques.  Cet abécédaire explique comment inclure l’archivage et la préservation dans les processus de gestion des données pour l’ensemble du cycle de vie des données.

