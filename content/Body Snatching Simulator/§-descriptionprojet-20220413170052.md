---
title: "Edaci - Description du projet"
date: 2022-04-13
id: 20220413170052
keywords:
reference-section-title: Références
nocite: ""
author: Fumet
---
# **Code de classement des fichiers**
_Ces sigles sont avant la date du fichier, question qu'ils soient catégorisés ensemble, comme s'il s'agissait d'un document._
_Le plus possible, un ficher agit comme un document._

### §-
présente un fichier important, tel ce présent portant sur la description du projet. Les fichiers concernant le lore ou les personnages ne sont pas censé avoir ce descriptif. Il s'agit plutôt de types de fichiers décrivant la raison d'être du document.

### §-gdd-
Game design document. Fichier, censé devenir très complet, présentant une description complète du jeu, tant d'un point de vue narratif et technique. Il s'agit d'offrir une manière le plus clair possible ce que le jeu est censé être et comment il sera développé et ce qu'il cherche à faire (public cible, plateforme, etc.). Ultimement, chaque fichier -1- devrait être peaufiné et résumé dans ce fichier.

### 1 -
Fichier non-officiel et qui n'est que sous-formes d'idées. Ce sont mes notes et mes idées en d'autres mots. Ce code précède tous les autres codes. Le code est "1" plutôt que "i" afin qu'il soit toujours devant les autres fichiers tentant d'être le jeu lui-même. Ex. : 1-gd-titre-date. Dans le meilleur des mondes, les fichiers "1" ne devrait être lié qu'entre eux. Je dois tenter de ne pas établir des hyperliens et wikilink entre des fichiers "officiels" et des "1dées", question de garder une cohésion entre ce qui est mes notes, et ce qui devra se trouver dans le jeu.

### -00-
Présente un fichier comportant une fleeting scène, c'est-à-dire une scène qui n'a pas de structure, qui n'est pas nécessairement canon et qui n'est pas encore positionné dans le scénario général. Encore qu'une idée.

### -0123-
Présente l'ordre d'apparition. Accolé avec la code "sc", il s'agit ainsi des chapitres du scénario. Cependant, accolé à "em" ou encore "pr", "lr", cela peut permettre de définir leur ordre d'apparition dans le jeu (à voir dans un cas non linéaire).
Vu l'efficacité de .yarn pour écrire un texte à choix multiples, les scènes principales sont écrite en .yarn (ou peut-être autre selon si je commence à utiliser ink ou pas). Les scènes sont numérotés de 001 à l'infini : 000-a-date-titre.yarn.

### -a-
"abc" étant la version du fichier ou encore s'il s'agit d'un sous-fichier relié au fichier principal (non lettré). Comme un sous-document servant de note ou de mise en contexte ou encore une annexe. Plus il y a de lettre, plus il y a d'annexe (A-A-A) **Une ancienne version de ce types de fichiers se trouvera dans le document Archive. Plus une version du fichier est récente, plus elle aura un numéro élevée (0123-13-a-6-titre-date)**
**Pour ces raisons, les fichiers annexes devront toujours être archivés avec le principal question de garder la liaison. Autrement, celle-ci devra se trouver comme hyperlien.**
** Ces fichiers semblent plus être un pain in the ass à gérer en plus de ne pas tant être pertinent. À voir. Comme le scénario d'un jv se veut non linéaire, il peut être intéressant de penser à l'annexe**.

### gd-
Fichier sur le game design et gameplay. Ces fichiers, s'ils ne sont pas dans la catégories des idées, représentent la description des mécaniques tel qu'apparaît en jeu. En bref, ce sont les tutoriels.

### ite-
Fichier sur les items du jeu. Dans le cas de ce projet, je doute qu'il y ait des items. Si c'est le cas, il s'agira de consommable. Peut-être même je vais choisir de ditch la description des items afin de forcer la lecture des fichiers annexes "tx" afin de comprendre leur fonctionnement.

### lr-
Fichier sur le lore. En jeu, il s'agit principalement d'un lexique.

### npc-
Fichier sur les npc et leurs dialogues. Il ne s'agit pas d'une description de ces derniers. Cela est dans "pr". En jeu, il s'agit de personnage annexe avec qui il est possible de parler en dehors de ce qui défini la tramer narrative, représentée par "sc".

### per-
Fichier sur les personnages. Si "1" n'est pas présent, alors il s'agit d'une description in-game du personnage. Une fiche se mettant à jour donc selon les conditions atteintes.

### sc-
Fichier sur le scénario. Si ce fichier n'est pas accompagné du code "1" ou "000" ou "00", alors il s'agit non pas de notes ou de scènes, mais de résumés in game du scénario.

### tx-
Fichier annexe présentant du texte afin de nourrir le lore du jeu. En soi, ces fichiers correspondent à la fois à lr et npc, mais diffèrent par leur présentation, étant des entrées parsemées à travers le jeu comme un article de journal par exemple. Techniquement, les fichiers "tx" ne devraient apparaître que dans la Neige [[1-gd-neige-20221104011212]].

## Exemple de terminologie : 
* §-titre-date
* 1-gd-choixdialogue-date
* sc-001-edacietpierre-date
* 1-sc-001-a-pierre-date
* 1-sc-001-2-a-1-pierre-date


# Edaci - Description du projet

Edaci, L'Onde Suceuse d'Ambre, raconte l'histoire d'une humanité dépossédée de sa pseudo-singularité et asséchée par le temps. Ceci est un vieux projet de ma part que je vais ici tenter de revivre tranquillement. Comme cet univers ce passe sur plusieurs milliers d'années, il sera séparé en différents projets.

### 20220629183612 - A Body Snatching Simulator - A self-ditching simulator

Cette version reprend le personnage de Krammandërn, cette fois-ci sans nom, majoritairement nommé _L'Edaci_, et agenre. Suite au vol de son corps d'origine, l'Edaci erre dans un désert de cendre jusqu'au temps où une tempête vienne à bout du corps dans le quel iel a été entreposé. Sa Mémoire est heureusement retrouvé par une humaine se faisant passer pour une Edaci. Elle l'injecte dans un ordinateur avant de par la suite lui donner le corps d'un pseudo-animal artificiel frankenstainisé et à moitié détruit. Un corps temporaire avec lequel l'Edaci doit parvenir à se trouver un de meilleur qualité.

Le but premier du jeu est évident : L'Edaci prend la fille pour une autre Edaci (Eidole ou Objicio serait son nom) et voudra "arracher" son corps pour soi-même. Bien qu'ultimement, iel préférerait retrouver son propre corps.
Il y aura d'autres personnages représentant différentes thématiques existentielles des robots que l'avatar pourra s'accaparer selon la préférence des joueureuses.

### Objectification des corps et des buts.

Le jeu est une sorte de déconstruction du dating simulator (ou encore de l'otome et bishoujo game si on veut, mais là ça va loin). Un dating sim présente habituellement une multitude de personnages à conquérir et charmer par la répétition menant à les connaître par coeur. Cela peut amener à différentes problématique du genre au niveau de ses mécaniques lorsqu'un jeu veut par exemple tenter de l'objectification de ses personnages. Un otome game comme Boyfriend Dungeon est une expérimentation intéressante comme parvient à faire en sorte que les personnages ne sont pas tant objectifié en des buts à conquérir par sa narration, comme ce sont ces personnages qui viennent vers nous. Seulement, cela n'empêche que ces personnages et la relation avec est une mécanique de jeu et ainsi, par définition, objectifié en but.

L'objectification des personnages et des relations dans un dating sim se fait alors à 2 niveaux :
* Le personnage est objectifié comme un objet de fantasme (design et souvent selon son rapport avec ce dernier, comme le protéger ou l'aider).
    * Objectification du corps.
    * Objectification de la relation.
    * Objectification du caractère, etc.
* Le personnage est objectifié comme but ludique, étant la centrale aux mécaniques du jeux (soit charmer le personnage).

Si on peut retravailler ces rapports selon sa manière de narrer le scénario, au niveau des mécaniques, cela semble moins évident et peut au final amener à un questionnement dépassant le sensationnalisme médiatique et xénophobe autour des dating sim, mais par rapport au jeu vidéo, voir l'informatique et la programmation, et son rapport  l'objectification du monde à travers des règles prévisibles. Cela amène évidemment à un débat moral face au cybernétisme et autres courant en découlant.

### A Dating Simulator about possession and singularity

Ainsi vient l'idée de ce jeu. Jouer et abuser avec cette réalité du dating sim afin d'explorer s'il ne serait pas possible de l'amener ailleur, de le repenser non pas qu'au niveau narratif, mais aussi ludique.

Il me semble possible de jouer avec le dating sim surtout quand on le sort de son but d'origine, soit dater des personnages. Vient l'idée du [[§-20220330171521-description-projet]] _Simulateur de Réseautage Universitaire_ où l'objectification des relations joue avec la cryptomancie et le réseautage où l'on entre en relation avec les gens non nécessairement pour le plaisir d'échanger, mais plutôt afin de pousser son propre développement personnel, quitte à user des autres comme une simple marchandise de l'information et de la morale (chambre à écho). 

Enfin, vient celle de ce jeu. En portant le focus sur un robot vivant dans un monde aux allures de la loi du plus fort, le jeu peut exploiter sans malaise les différents malaises qu'amène par définition le dating simulator. Ainsi, notre avatar objectifie carrément les autres personnages comme des buts à conquérir afin de voler leur corps. Et ce qui l'amène à déterminer quel corps voler est directement relié à l'objectification de ceux-ci et non via un raisonnement particulier.

Du moins, en surfance.

Là vient la beauté de l'idée. Il serait possible de tranquillement ajouter plusieurs couches de nuances afin de remettre en perspective les choix de l'avatar et ses buts et son rapport au corps. Chaque personnage représente au rapport différent à son propre corps et oblige l'avatar à revoir pourquoi de base iel désir arracher ces corps plutôt que de reconstruire son propre corps, nouveau. Cela amène aussi à un questionnement face à la nostalgie, la peur du changement et l'identité close, comme le personnage désir ultimement récupérer son corps d'origine.

Le tout est encore à travailler, mais je crois toucher avec cette idée un beau champ de travail afin de pousser le dating sim jusqu'au bout de ses entrailles. (au niveau symbolique évidemment, sinon je devrais faire en sorte qu'on puisse écrire/parler librement aux personnages et entretenir une relation avec...).

Cela implique que chaque grosse mécanique du dating sim devrait être présente dans le jeu, mais amener à des résultats différents de ceux d'habitudes, ou encore que leurs rapports aux personnages soient plus consciencieux.
* Grind des statistiques
* Cadeaux.
* Choix de réponses.
* Possibilité de sauvegarder afin de revenir sur ses choix et mieux "conquérir" les personnages (le dating sim est en réalité un type de jeu très meta comme il faut apprendre à connaître les personnages et ainsi les manipuler, et cela se fait ultimement via la sauvegarde qui permet d'effacer toutes ses erreurs et d'expérimenter sans conséquences - C'est d'ailleurs pourquoi Tokimeki rend son système de sauvegarde si bordélique je crois, afin de garder une difficulté en ce sens).

### Déconstruire son identité

 Voici quelques idées sur comment je pourrais atteindre cela:
 * Chaque personnage à "dater" représente une questionnement sur l'identité et la singularité qui hante l'Edaci, mais qu'en surface. C'est-à-dire, en réalité, ces personnages _ne permettent pas réellement à l'Edaci de se questionner sur sa propre identité_, du moins, pas comme iel le souhaiterait. Ainsi, ce qui est d'abord une objectification des personnages comme étant un moyen servant à nourrir sa propre personne fini par devenir des êtres sensibles qui possèdent leurs propres intérêt qui ne concernent aucunement l'Edaci et dont iel ne pourra avoir d'influence ou de gain sur. D'ailleurs, il pourrait être amusant de faire en sorte qu'un des personnages agisse avec l'Edaci comme s'iel était LEA personnage à conquérir. Bref, faire en sorte qu'un personnage objectifie l'Edaci.
 * Chaque personnage est imprévisible. Mais niveau ludique ce pourrait être chiant. En même temps, cela rendrait le jeu moins scripté et plus porté à user d'AI complexe, ce pourrait être trop dur à faire aussi.
 * Les personnages ne sont pas nécessairement possible à "conquérir". Eidole qui serait au final une humaine en est un exemple. Voir, un personnage pourrait paraître encore plus nébuleux et inconnu face à l'avatar à force d'apprendre à le connaître.
 * Les sauvegardes sont diététiques et les personnages se rendent compte que l'Edaci save, mais implémenter cela pourrait être compliqué.
 * Il faudrait que je réfléchisse par rapport à comment déconstruire le grind et les cadeaux.
 
### Agentivité et malhonnêté
Ultimement, le but du jeu est de faire en sorte que les personnages aient leur propre agency, narrativement parlant, plutôt qu'être des objets servant l'avatar et le scénario. Cela pourrait cependant amener à certaine problématioque, soit l'impression que le jeu est malhonnête, voir malvaillant avec lea joueureuse. Après tout, si un jeu de relation s'amuse à les rendre imprévisible ou à constamment les déconstruire dans la face de lea jouereuse, cela pourrait être perçu comme un jeu insultant. Au moins, le fait qu'il s'agisse d'un robot voulant voler des corps (et reconstruire son identité à travers les autres) peut permettre de faire en sorte de ne pas attaquer les gens sur des sujets ouvertement trop sensible, comme pourrait l'être si le jeu restait sur le terme de la romance (quoi que, je vais clairement jouer avec le lien entre possession et amour).

Cependant, comme ultimement, la morale du jeu sera de faire réaliser à l'avatar qu'il peut très bien reconstruire son identité par soi-même et son rapport avec les gens et non seulement en usant des autres ou en retrouvant son corps d'origine, pourrait peut-être être assez pour montrer que le jeu veut en réalité être bienveillant.