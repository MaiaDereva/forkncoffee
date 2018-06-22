Déclaration d'intentions et contexte du projet Forkncoffe, conception de plateformes libres et décentralisées (et peut-être fédérées) en structure libre (free framework) pour faire coworking ou tiers-lieux presque partout et faire paysages en communs par strates (layers) distribuées.

#### tables de contenues
1. [Contexte et intentions](#contexte-et-intentions)
  + 1.1 [Orgines](#origines)
  + 1.2 [Démarches liées et projets connectés](#démarches-liées-et-projets-connectés)
  + 1.3 [Environnement actuel du terrain](#environnement-actuels-du-terrain)
  + 1.4 [Visions](#visions)
  + 1.5 [Intentions](#intentions)
2. [Intentions](#intentions)
  + 2.1 [Proposition de valeur](#proposition-de-valeur)
  + 2.2 [Gouvernance](#gouvernance)
    + [Pouquoi](#pourquoi)
    + [Qui](#qui)
    + [Pourqui](#pourqui)
    + [Comment](#comment)
  + 2.3 [Objet de l'action](#objet-de-l'action)
  + 2.4 [Temps de travail](#temps-de-travail)
  + 2.5 [Argent](#argent)
  + 2.6 [Technologies et techniques](#technologies-et-techniques)
    + [Langage Elm](#langage-elm)
    + [Apprendre en faisant](#apprendre-en-faisant)
    + [Partager en faisant](#partager-faisant)
    + [Hygiène numérique](#hygiène-numérique)
    + [Intimité et données personnelles](#intimité-et-données-personnelles)
    + [Sécurité](#sécurité)
3. [Remerciements](#remerciements)

# Contexte et Intentions

## Contexte

Repenser la qualité de vie, les conditions de travail et les productions attendues en appliquant les mêmes cultures et recettes que celles du 20ème siècle ne mènera pas à des résultats différents.

Nous avons aujourd'hui presque toutes les briques culturelles, intellectuelles, technologiques et retours d'expériences, nécessaires à une mutation vers plus de soutenabilité. Mais nous marchons toujours dans les sentiers d'une industrialisation concentrative et en silo des conditions de travail. 

Que pouvons-nous mettre en œuvre pour améliorer nos conditions et permettre à de meilleures circonstances de voir le jour ?

### Origines

Marseille 2012, avec trois personnes nous lancions Workncoffee, via un wordpress cheap <https://marseilleworkncoffee.wordpress.com>, basé sur la une volonté d'exaptation du travail. L'exaptation est une adaptation sélective opportuniste, privilégiant des caractères qui sont utiles à une nouvelle fonction, pour laquelle ils n'avaient pas été initialement sélectionnés. Par exemple, lors d'une baisse de la quantité d’oxygène dans l'eau des lagunes au carbonifère, les tétrapodes se sont mis à utiliser un sac respiratoire (ancêtre des poumons) pour s'adapter à la vie terrestre et la respiration aérienne. Un organe qui n'était auparavant pas utilisé lors de leur vie en milieu aquatique.

> _Les exaptations sont la reconfiguration créative de la technologie par leurs utilisateurs, soit en tant que sous-produit d'une fonction précédente (co-optation), soit en tant que produit d'une fonction précédente (co-option). 

Pour faire plus simple, nous cherchions à concevoir des circonstances de rencontres entre individus de sphères professionnelles différentes, nous voulions faire tiers-lieux libres presque n'importe où, nous visions les qualités de nos conditions de travail. Café de quartiers, plages, salle associative, appartement, studio d'enregistrement... Nous avons testé de nombreux spots de coworking qui, à l'époque, semblaient « insolites » pour beaucoup de monde. Cela nous à coûté moins cher que les bureaux partagés co-working business de l'époque à Marseille ; cela à permis des rencontres avec des marin-pêcheurs ; cela a été fait avec plus de libertés et de conforts que ne le permettaient les espaces auto-proclamés co-working.

Lors de cette expérience courte mais intense, une petite communauté d'une cinquante de personne s'était formée. Nous avons surtout appris que cela plaisait beaucoup aux commerçants indépendants, aux associations, et d'autres, de voir des développeuses et développeurs, juristes, graphistes, étudiant⋅e⋅s, entrepreneur⋅e⋅s, freelances, venir travailler à leurs côtés. Nous avons appris que le blogging décrivant lieux et recettes pour travailler de manière insolite pouvait faciliter les circonstances de rencontres.
o
J'ai quitté Marseille et workncoffee fin 2013, voyant Marseille comme un terrain de jeu de coworking de 240 km² et ses 111 quartiers.

Les intuitions qui étaient nées de cette 1ère expérience sont :
+ Les conditions et circonstances de rencontres sont un schéma = **Pattern**
+ Des blogs et un site internet avec documentation peuvent préfigurer une esquisse de structure de fonctionnement = **Framework**
+ Les cartes que nous faisons avec les histoires qui les accompagnent sont des strates géographiques et sociologiques = **Layer**

De 2013 à 2018 j'ai participé à plusieurs divers projets concernant les mutations du travail et les organisations novatrices, soit comme contributeur, soit comme fondateur-contributeur.

Ce qui donne par exemple : 

<https://www.youtube.com/embed/oNhMK6sgLFA>
![](/assets/blog/images/nevez.png)

Dont la documentation est ici : <http://movilab.org/index.php?title=IndieCamp_2017_N%C3%A9vez>

### Démarches liées et projets connectés

Ces démarches et projets nourrissent les réfléxions sur les problématiques auxquelles forkncoffee tente de répondre, elles permettent également des apports méthodologiques, techniques et techologiques au projet.

+ movilab.org, le wiki des tiers-lieux libres et open source - [contributeur](http://movilab.org/index.php?title=Utilisateur:XavCC)
+ [indiecamp](http://movilab.org/index.php?title=IndieCamp), format libre de tiers-lieux éphémère en milieu rural - fondateur-contributeur
+ [multbao.org + repo nomades](http://www.multibao.org), la boite à outils des organisations collaboratives - [contributeur et mianteneur](https://github.com/orgs/multibao/teams/gestionnaires/members).
+ [walkingdev](http://walkingdev.fr), découvrir les choses du web et apprendre en marchant - contributeur
+ [devffreindlyplaces](https://github.com/XavCC/devfriendlyplaces), catographies des lieux où travailler hors des murs - contributeur
+ [fork the world](https://world-trust-foundation.gitbooks.io/fork-the-world/content), livre numérique sur les mutations du travail - contributeur
+ [Bretgane lab tour 2015](https://xavcc.gitbooks.io/vivre-ensemble-faire-ensemble/content), tour de Bretagne des fablabs - fondateur-contributeur
+ [LabOSe 2016](https://paper.dropbox.com/doc/LabOSe-Laboratoire-open-source-dexperiences-libres-et-distribuees-KwBdA6CpH17tiqPcCgmfW), laboratoire itinérant des pratiques collaboratives dans les Communs - fondateur-contributeur
+ [Biome community](http://umap.openstreetmap.fr/fr/map/we-are-biomers_148365#4/40.48/-46.45), hacklab de biomimétisme et communauté étendue
+ [DAISEE](https://daisee.org), Internets of energy, energy as a common - contributeur

### Environnement actuel du terrain

L'annonce « [Fermeture de La Mutinerie : la fin de l’innocence du coworking](https://www.helloopenworld.com/la-fin-de-linnocence-du-coworking-5762) » au printemps 2018 mettait en visibilité un changement profond démarré il y a quelques années : Le coworking est devenu un business sans pratiques communautaires collaboratives.

Pourtant, nous avons depuis peu une définition scientifique universitaire des tiers-lieux par le docteur Antoine Burret, dans sa thèse [Etude de la configuration en Tiers-Lieu - La repolitisation par le service](http://movilab.org/index.php?title=Etude_de_la_configuration_en_Tiers-Lieu_-_La_repolitisation_par_le_service) :

> « _Celle-ci envisage le tiers-lieu comme une configuration sociale particulière où se produit une rencontre entre des entités individuées qui s’engagent intentionnellement à la conception d’une représentation commune, c’est-à-dire à responsabilité partagée. Des invariants sont enfin posés comme l’esquisse d’une logique opératoire supposée déterminer la présence de la configuration en tiers-lieu._ »

Alors si conditions de travail, coworking et tiers-lieux, souffrent de maux, nous pouvons regarder cela au prisme d'événements contemporains et les comparer à des mécanismes identifiables. 

Github est racheté par Microsoft, ce qui inquiète 95% des producteurs du code source des logiciels libres puisqu'ils sont présents sur la plateforme github qui était déjà avant son rachat une entreprise de droit privé ; et Microsoft était déjà le plus gros contributeur à github. C'est la concentration qui est dangereuse dans ce processus. Apparait alors les questions de migrer vers vers Gitlab.org : savez-vous que Google est en fait un énorme investisseur dans Gitlab, entreprise de droit privé ?

Le problème n'est pas que Microsoft achète Github. Il s'agit de centralisation et de silos. Vous ne résoudrez pas cela en déplaçant vos données d'un silo à l'autre.

Les coworking et tiers-lieux libres et open source ont leur portail informationnel, <http://movilab.org>, qui contient recettes, retour d'expériences, documentation de processus et configuration sociale, de nombreuses données. Mais ce portail ne favorise pas les condtions de rencontre pour faire tiers-lieux presque n'importe où. Car il s'agit bien de faire tiers-lieux et non de limiter cette configuration sociale particulière et les responsabilités partagées à simplement quatre murs et un toit, et encore moins à des frontières administratives.

Il y a des centaines d'intiatives d'agrégation des tiers-lieux, mais rien de décentralisé ni fédéré, parfois même avec des systèmes non-libres. 

Alors, comment aller « Vers des espaces ouverts et partagés » ([Simon Sarazin](http://simons.fr/blog/2016/12/21/vers-des-espaces-ouverts-et-partages/)), nous avons besoin de favoriser des cultures libres et de la compostabilité d'un écosystème.

De la compostabilité :
+ elle se pense et se prépare très en amont,
+ elle permet de mettre fin aux projets lorsque nécessaire tout en leur assurant un nouveau départ,
+ elle nécessite le partage sincère de l’ensemble des ressources produites.

Rendre son projet compostable, c’est fertiliser les idées en les partageant et tendre vers des organisations plus vivantes, vivaces et vivables. (source [Romain Lalande](https://vecam.org/La-compostabilite-pour-un-ecosysteme-de-projets-vivaces))

Il y a une galaxie d'initiatives tiers-lieux, tiers-jardin, coworking rural, graines libres, jardin partagé, artisans responsables et solidaires, bars alternatifs, qui voient leurs paysages se faire racheter ou dévorer par des industries de la centralisation et/ou être invisibilisés sous des silos de communication.

Nous n'avons pas encore franchi le passage vers une proposition d'ossature (framework) facilitant l'acquisition par l'expérience vécue des briques culturelles, intellectuelles, technologiques, pour déployer de façon distribuée les conditions et circonstances de rencontres pour laisser émerger des situations brisant les silos et concentrations en fournissant une décentralisation fédérée (voir [backlog](https://github.com/XavCC/forkncoffee/projects)).

### Visions

Essayons de faire de forkncoffee une des étapes vers ces ossatures avec un prototype sous licence dans le domaine public, avec des documentations, blogging, cartes géographiques et jeux de données, distribués, décentralisés et fédérés.

Forkncoffee est un projet pour les rassembler et gouverner tous ? Non ! Car investigué pour être basé sur un principe de fédération (voir [backlog](https://github.com/XavCC/forkncoffee/projects/1)).

De simples cartes géographiques ? Non ! Des paysages de données commentées par celles et ceux qui les font et non limitées à des frontières administratives ; et surtout des cartes, et non une carte, avec des interstices, et non plus de frontières territoriales, qui penvent se chevaucher pour rendre visibles les interconnexions entre les communautés de pratiques. 

Forkncoffee est un simple site internet avec des cartes et des publications ? Non ! Car il peut facilement devenir l'outil qu'une personne copie et modifie pour l'adapter aux besoins d'autres micro-groupes sociaux (AMAPa, FabLabs, fédérations des amateurs de cerf-volant, professionnel de la micro-brasserie...), par ces licences libres, par la documentations, par [le livre numérique](https://xavcc.gitbooks.io/elm-chaos/content), par les rencontres et les partages. 

Nous devons réapprendre à comprendre nos techniques et nos outils, nous avons intérêt à réapprendre à concevoir par nous-même nos techniques et nos outils.

**Exemples** :

Le plus bel espace pour faire tiers-lieu ou coworking à Nantes est la serre tropicale du jardin des plantes, il est gratuit et assez bien équipé et confortable, mais presque personne ne sait que ces condtions y sont réunies pour faire tiers-lieu.

![](/assets/blog/images/serre_nantes.jpeg)

À Rennes, un jardin de 300 m² sur les bords de la rivière est un contexte méconnu pour se rassembler et travailler à plusieurs, sans obligatoirement se connaître en amont, en s'engageant dans une représentation commune et des responsabilités partagées.
![](/assets/blog/images/rennes-jardin.jpg)

## Intentions

Tout en apprenant et en concevant un prototype technologique partagé et documenté au jour le jour, il est important d'essayer d'apporter des conditions nouvelles pour répondre aux problèmes décrits précédemment. Il s'agit de prototyper en itération permanente, de sortir des cartes de routes (roadmap) pour tenter un fonctionnement chaotique (chaos map), de collaborer au mieux à plusieurs et de documenter techniques, méthodologies et technologies en temps quasi instantané. Ceci dans la visée de ne pas suivre un chemin unique déjà arpenté et balisé, mais de défricher des possibles et de s'ouvrir des champs de focntionnement dont les mécanismes de pensées ne sont pas les mêmes que les mécanismes de pensées qui ont engendré ces problèmes. 

### Proposition de valeur

Là où les réseaux sociaux proposent un jugement de valeur ou une évaluation par « like » ou « votes » individualisés, forkncoffee postule un partage de réalisation et de documentation placées dans une géographie contextualisée par le vécu du collectif avec des ressources libres et open source.  

Cela revient à « Refaire le monde en tiers-lieux libres et open source » en fournissant prétextes, moyens, outils, techniques, technologies, documentations et rencontres pour que toute personne ou groupe de personnes qui le désirent puisse avoir sa propre instance frokncoffee (appelée ainsi ou renommée librement selon les volontés).

### Gouvernance

_en cours de rédaction_

#### Pourquoi
_en cours de rédaction_

#### Qui

Forkncoffee est, au 1er juin 2018, porté et développé par Xavier Coadic. Du fait des intentions collaboratives du projet et des licences libres et domaines publics des codes source et supports annexes, forkncoffee est explicitement ouvert à toute contribution, récupération, modification, sous respect des licences attribuées.

#### Pour qui
Porteuses ou porteurs de projets collaboratifs et/ou coopératifs, individu cherchant des condtions de travail soutenables et partagées, collectif, artisans, entrepreneur⋅e, association, collectivité, entreprise, écoles, universités...

Les mutations du travail et les mutations des conditions d'exercice de son travail ne sont pas limitées à un public cible mais impactent l'ensemble de la population dans des paysages de vies. 

Toute personne, ou organisation décidant de s'impliquer de près ou de loin dans forkncoffee, peut révendiquer le droit et les responsabilités de participer à la gouvernance partagée du projet localement ou globalement. 

#### Comment

_en cours de rédaction ; **pattern**, **structures libres** et **strates**_

![](/assets/blog/images/layerscommonslandscape_2.jpg)

Faire Paysages en Communs

![](/assets/blog/images/layerscommonslandscape_3.jpg)

### Objet de l'action

Forkhcoffee a pour objet de faciliter, via une une application web en lange de programmation elm, les possibilités pour un plus grand nombre de personne de « [refaire le monde en tiers-lieu](http://movilab.org/index.php?title=Refaire_le_monde_en_tiers-lieu) ».

1. **favoriser une configuration sociale** par les _patterns_ :  ce qu’est le tiers-lieu avant toute chose. Le terme de tiers-lieu désigne une structure relationnelle entre des êtres humains dans un environnement (technique et non technique). Prenons pour exemple le cas où plusieurs personnes sont rassemblées dans un serre publique et qu’elles participent à une même situation de création, qui pourrait être une séance de pair programming. Dès lors, ce que l’on nomme « configuration sociale » est l’ensemble des tensions, des actions, des interdépendances et des relations réciproques qui se nouent entre les personnes. De cette perspective, le tiers-lieu est compris comme la structure globale que forment les personnes lorsqu’elles sont réunies par cette même activité.

2. **faciliter des rencontres entre des entités individuées** par _les structures libres_ : la condition minimale pour qu’il y ait tiers-lieu. Deux entités indépendantes se réunissent et interagissent dans un lieu identifié. Peu importe les raisons de leur rencontre, c’est celle-ci – dans sa temporalité et sa géographie – qui fait d’un endroit quelconque ou d’une place anonyme le lieu. La rencontre qui « fait le lieu » peut advenir autant sur une place publique dans une ville, un bâtiment en friche, une maison particulière, une gare ou un commerce de proximité, un laboratoire citoyen de fabrication numérique...

3. **Catalyser un engagement intentionnel** par les _strates_: un engagement entre les personnes (entités/mondes différents) voit le jour grâce à la rencontre. Puisqu’il n’y a pas de lien formel en amont de la rencontre, les personnes discutent des termes de leur engagement. Elles entrent en négociation pour parvenir à un accord qui peut être le fruit d’un compromis, d’un consensus (apparent ou réel), d’un consentement mutuel ou bien d’une décision autoritaire de l’une des personnes derrière laquelle les autres se replient volontairement.

4. **Co-cartographier des paysages communs** : par l'appui de l'application forkncoffee permettant la cnception et le partage de documentation, de récits, ainsi que de cartes géographiques des composés des tiers-lieux co-conçus par les circonstances de rencontres, un ensemble de paysages communs se dessinent, sans être contraint par des limites administratives territoriales. Offrant ainsi un jardin de collaboration et d'expérimentation libre avec peu de silos, offrant également une nouvelle grille de lecture et d'analyse du concept tiers-lieu et de ses réalités environnementales, sociales et économiques.

### Temps de travail

Forkncoffee est démarré au 1er juin 2018, la sortie prévue est 10 septembre 2018. 3 mois de travail sérieux et appliqué ainsi qu'un livre numérique alimenté pas à pas sur l'expérience d'apprentissage et de partage du langage elm et du projet fokncoffee.

C'est un temps délibérément choisi pour faciliter la compréhension et l'intégration des concepts en langage elm, c'est un temps permettant une démarche itérative non-linéaire d'apprentissage et de partage, dméarche qui pourrait être reproduite par la suite pour d'autres groupes apprenants. 

Je souhaite inscrire cela dans une carte chaotique (choas map) par opposition à une carte de route (raodmap) standardisée afin de tester et de documenter cette expérience d'apprentissage par le faire qui ne rentre pas dans les cahiers des charges habituels. Ceci sera notamment matérialisé par l'écriture d'un [livre numérique sous licence libre](https://xavcc.gitbooks.io/elm-chaos/content)). 

![](/assets/blog/images/documentation.jpg)

### Argent

L'argent n'est pas une chose sale, l'argent est nécessaire pour développer des projets. C'est l'origine de cet argent et l'usage que l'on en fait qui induisent une qualité, propore ou sale, à cet argent.

J'ai donc pris le parti de proposer de financer ce projet fokncoffee par une campagne de dons libres provenant de personnes trouvant un intérêt à cette démarche. Au-delà de l'aspect projet et du temps de développement web de la première version du prototype forkncoffee, je propose également d'alimenter le plus régulièrement possible le livre numérique, également sous licence libre, afin de fournir les traces documentées d'un processus chaotique d'apprentissage du langage elm au travers des avancées de ce projet. C'est le concept du « Apprendre en faisant, apprendre en partageant ». Ces efforts sont fournis pour partager un maximin de savoirs libres, savoir-faire et savoir-être, ainsi qu'à favoriser l'approriation et la réutilisation des processus qui mènent à un prototype et le livre est intitulé « [Elm : apprendre par le chaos d'un prototype](https://xavcc.gitbooks.io/elm-chaos/content) »

La campagne de dons vise ainsi à permettre d'alimenter et maintenir ces deux faces du projet.

**L'objectif minimum est de 500€ avant le 30 juin 2018***, avec un espoir de 1000€ avant les 3 mois de travail. Commencé au 1er juin, date de sortie 10 spetembre 2018. 

Pour soutenir, 3 moyens possibles : 

<p align="center">
    <b><a href="https://paypal.me/pools/c/84Ug9UH2cW">Collecte sur Paypal</a></b>
    |
    <b><a href="https://g1.duniter.fr#/app/wot/92UU85KeAXuVjvnfyXWxPkcTSeE68Ftt4D53tJVVNrgN/Xavier%20Coadic">don en Ğ1 - Duniter</a></b>
    |
   <b><a href="https://liberapay.com/Xav.CC">petits dons hebdomadaires sur Liberapay</a></b>
</p>

+ Pour l'atteinte du palier de 500€ : le code de forkncoffee est intégralement publié en version 
+ Pour le palier de 1000€ : forkncoffee est « officiellement » lancé le 10 septembre

Au-delà de ces paliers :

+ Pour 1 500€ : forkncoffee intègre une ou plusieurs interfaces graphiques codées en elm pour faciliter la contribution
+ plus de 1 500€ : l'argent sera reversé en plusieurs dons à d'autres projets libres et open source.

### Technologies et techniques

_en cours de rédaction_
#### Langage Elm

_en cours de rédaction_
#### Apprendre en faisant

_en cours de rédaction_
#### Partager en faisant

_en cours de rédaction_
#### Hygiène numérique

_en cours de rédaction_
#### Intimité et données personnelles

_en cours de rédaction_
#### Sécurité 
_En cours d'investigation_

# Remerciements
Maïa Dereva, Émile Hooge, dr4Ke, pour vos soutiens des permiers jours. 
