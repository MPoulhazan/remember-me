# remember-me
All tips for FullStack Devs

## Maven

### Add prop file to config Intellij
```--spring.config.location=./src/test/resources/toto.yml --spring.config.name=toto.yml```

### Clean install skip SSL
```mvn clean install -U -Dmaven.wagon.http.ssl.insecure=true```

### Set Swagger active
```--spring.profiles.active=swagger```

### Set config profil dev
Ajouter la VM options suivante :
```-Dspring.profiles.active=dev```


## Commandes Linux
```alias```
La commande alias est un moyen d’exécuter une commande ou une série de commandes Unix en utilisant un nom plus court que ceux qui sont généralement associés à ces commandes.

```apt-get```
L’outil apt-get met automatiquement à jour une machine Debian et installe les packages et programmes propres à Debian.

```AWK, Gawk```
AWK est un outil qui fonctionne comme un langage de programmation et qu’on utilise pour manipuler du texte. La programmation de AWK ressemble à celle du shell dans de nombreux domaines, mais la syntaxe de AWK lui est propre. Gawk est la version du projet GNU du langage de programmation AWK.

```bzip2```
Un programme portable, rapide et open source qui compresse et décompresse les fichiers à un rythme élevé, mais qui ne les archive pas.

```cat```
Une commande Unix/Linux qui peut lire, modifier ou concaténer des fichiers texte. La commande cat affiche également le contenu des fichiers.

```cd```
La commande cd modifie le répertoire courant dans Linux et permet de basculer facilement entre les répertoires. La commande cd de Linux est similaire aux commandes CD et CHDIR de MS-DOS.

```chmod```
La commande chmod modifie les permissions d’un ou plusieurs fichiers. Seul le propriétaire du fichier – ou un utilisateur privilégié – peut changer le mode d’accès. La manière la plus simple de l’utiliser est de l’écrire sous la forme : chmod ugo+rwx <nom de fichier>, où où l’on précise que l’utilisateur en cours (u), son groupe d’utilisateurs (g) et les autres (o) ont désormais droit (+) de lecture (r), d’écriture (w) et d’exécution (x) pour le fichier indiqué. Les différentes lettres sont à indiquer ou non selon le droit que l’on souhaite accorder.

```chown```
La commande chown change la propriété du fichier ou du groupe. Il donne aux administrateurs la possibilité de changer la propriété de tous les objets dans une arborescence de répertoires (en précisant -R en amont du nom du répertoire racine), ainsi que la possibilité de consulter des informations sur les objets traités.

```cmp```
L’utilitaire cmp compare deux fichiers de n’importe quel type et écrit les différences sur la sortie standard. Par défaut, cmp est silencieux si les fichiers sont identiques. S’ils diffèrent, cmp indique l’octet et le numéro de ligne où la première différence s’est produite.

```comm```
Les administrateurs utilisent comm pour comparer les lignes communes aux fichiers 1 et 2. La sortie se fait en trois colonnes, de gauche à droite : lignes uniques au fichier1, lignes uniques au fichier2 et lignes communes aux deux fichiers.

```cp```
La commande cp copie les fichiers et les répertoires. Les copies peuvent être effectuées simultanément dans un autre répertoire, même si la copie porte un nom différent.

```Cpio```
La commande cpio copie les fichiers dans ou depuis une archive cpio ou tar. Une archive tar est un fichier qui contient d’autres fichiers, ainsi que des informations à leur sujet, telles que leur nom, leur propriétaire, leur date et leurs autorisations d’accès. L’archive peut être un autre fichier sur le disque, une bande magnétique ou un canal de sortie (pipe). Cette commande Linux a également trois modes de fonctionnement : copy-out, copy-in et copy-pass. C’est également une alternative plus efficace au à la commande tar.

```CRON```
CRON est un processus du système Linux qui sert à exécuter automatiquement un programme (un script le plus souvent) à un moment prédéterminé. Pour utiliser un script CRON, les administrateurs doivent préparer un fichier texte qui décrit le programme et le moment où ils veulent que CRON l’exécute. Ensuite, le programme crontab charge le fichier texte et exécute le programme à l’heure spécifiée.

```cURL```
Les administrateurs utilisent cURL pour transférer une URL. Cette commande est utile pour déterminer si une application peut atteindre un service en ligne et dans quelle mesure ce service répond correctement à la requête. Avec l’option -O, cette commande permet de télécharger dans le répertoire courant le fichier se trouvant à l’URL indiquée.

```declare```
La commande declare déclare les variables, leur donne des attributs ou modifie leurs propriétés.

```df```
Cette commande affiche la quantité d’espace disponible sur le système de fichiers – le volume – indiqué en paramètre. Sans paramètre, la commande df affiche l’espace disponible sur tous les systèmes de fichiers actuellement montés.

```echo```
Utilisez echo pour afficher une chaîne de caractères ou le contenu d’une variable sur la sortie standard.

```enable```
La commande enable permet d’arrêter ou de démarrer les impressions.

```env```
La commande env exécute un programme dans un environnement alternatif, avec ses propres variables, ou affiche l’environnement actuel et ses variables.

```eval```
La commande eval, suivie du nom d’une variable, permet d’exécuter en une fois toutes les commandes qui ont été enregistrées dans cette variable.

```exec```
Cette fonction exécute la commande entrée en argument en la positionnant, dans la liste des processus, à la place du processus parent, généralement le bash. Cela permet de ne pas retourner dans le terminal à la fin de l’exécution.

```exit```
La commande exit met fin à un script et renvoie une valeur au script parent.

```expect```
La commande expect parle à d’autres programmes interactifs via un script et attend une réponse, souvent sous la forme d’une chaîne de caractères qui correspond à un modèle donné.

```export```
La commande export exporte une variable de la session Shell en cours vers toutes les autres sessions Shell ouvertes depuis cette session. Sans la commande export, toutes les sessions Shell ouvertes ensuite partiront de variables vierges.

```find```
La commande find recherche dans l’arborescence des répertoires pour localiser des groupes particuliers de fichiers qui répondent aux critères indiqués en argument à l’aide des options -name, -type, -exec, -size, -mtime et -user.

```for, while```
Les commandes for et while exécutent ou mettent en boucle des éléments de manière répétée tant que certaines conditions sont remplies.

```free```
Avec la commande free, les administrateurs peuvent visualiser les quantités totale, libre et utilisée de mémoire physique et de mémoire virtuelle swap dans le système, ainsi que les tampons et le cache utilisés par le noyau.

```gawk```
Voir l’entrée Awk.

```grep```
La commande grep recherche une chaîne de caractères, ou un modèle donné de caractères, dans les fichiers et peut remplacer cette chaîne par une autre. C’est l’une des méthodes de recherche de fichiers dans Linux.

```gzip```
C’est le programme open source du projet GNU pour la compression des fichiers, qui sert notamment à compresser des pages web sur un serveur pour les décompresser dans le navigateur. Il est populaire pour la compression de médias en streaming et peut concaténer et compresser simultanément plusieurs flux.

```history```
La fonction history affiche toutes les commandes utilisées depuis le début de la session en cours.

```ifconfig```
La commande ifconfig configure les interfaces réseau gérées par le noyau au moment du démarrage. Elle n’est généralement nécessaire que lors du débogage ou du réglage du système.

```ifup```
Avec ifup, les administrateurs peuvent configurer une interface réseau et activer une connexion réseau.

```ifdown```
La commande ifdown ferme une interface réseau et désactive une connexion réseau.

```iptables```
La commande iptables permet ou bloque le trafic sur un hôte Linux et peut empêcher certaines applications de recevoir ou de transmettre une requête.

```kill```
kill est utilisée par les administrateurs pour envoyer un signal spécifique à un processus. Elle est le plus souvent utilisée pour arrêter en toute sécurité des processus ou des applications.

```less```
La commande less permet à l’administrateur de visualiser les fichiers de configuration et de log, en affichant les fichiers texte un écran à la fois, avec possibilité de naviguer en arrière ou en avant.

```locate```
La commande locate sert à localiser un fichier. L’utilisation de l’argument -i rendra la recherche insensible à la casse.

```lft```
La commande lft détermine les itinéraires que suivent les paquets sur un réseau. Elle fournit des informations pour déboguer les connexions, ou pour trouver l’emplacement d’un élément.

```ln```
La commande ln crée une nouvelle entrée dans le système de fichiers pour un fichier existant, ce qui permet par exemple d’utiliser un même fichier depuis deux répertoires différents.

```ls```
La commande ls liste les fichiers et les répertoires du répertoire de travail en cours. Elle permet par exemple aux administrateurs de voir quand les fichiers de configuration ont été modifiés pour la dernière fois.

```lsof```
Les administrateurs utilisent lsof pour répertorier tous les fichiers ouverts. Ils peuvent ajouter -u pour trouver le nombre de fichiers ouverts par un utilisateur en particulier.

```lsmod```
La commande lsmod affiche l’état des modules du noyau, ce qui aide à résoudre les problèmes de fonctionnement sur un serveur.

```man```
La commande man permet aux administrateurs d’afficher le manuel d’utilisation intégré aux distributions Linux, qui documente les commandes et d’autres aspects du système.

```more```
Identique à la commande less, more affiche sous forme de pages un fichier texte, un écran à la fois, mais ses options de navigation sont plus limitées.

```mount```
Cette commande permet de monter des systèmes de fichiers sur des serveurs. Elle répertorie également les systèmes de fichiers actuels et leur emplacement de montage, ce qui est utile pour localiser un disque qui ne répond plus ou en installer un nouveau.

```mkdir```
La commande mkdir crée un nouveau répertoire.

```neat```
Il s’agit d’un outil de l’environnement graphique Gnome qui permet aux administrateurs de spécifier les informations nécessaires à la mise en place d’une carte réseau.

```netconfig/netcfg```
Les administrateurs peuvent utiliser netconfig pour configurer un réseau, pour activer des appareils réseau ou encore afficher une série d’écrans qui invitent à entrer des informations de configuration.

```netstat```
Cette commande fournit des informations et des statistiques sur les protocoles utilisés et les connexions réseau TCP/IP en cours. Il s’agit d’un outil d’investigation utile pour déterminer quels sont les processus et les programmes actifs sur un ordinateur et qui sont impliqués dans les communications de réseau.

```nslookup```
Cette commande sert à trouver l’adresse IP qui correspond au nom d’hôte entré en paramètre, et vice-versa.

```od```
La commande od affiche les fichiers binaires au format octal (texte), hexadécimal ou binaire.

```passwd```
Les administrateurs utilisent passwd pour mettre à jour le mot de passe actuel d’un utilisateur.

```ping```
La commande ping vérifie qu’une adresse IP particulière existe et peut accepter des requêtes. Elle peut tester la connectivité et déterminer le temps de réponse, ainsi que s’assurer si l’ordinateur hôte d’un utilisateur est en activité.

```ps```
Les administrateurs utilisent ps pour obtenir l’état des processus en cours sur un système.

```pwd```
La commande print working directory (pwd) affiche le nom du répertoire de travail en cours.

```rcp```
Abréviation de "remote copy program" (programme de copie à distance), cette commande permet aux utilisateurs de copier des fichiers vers ou depuis un ordinateur distant ou entre des systèmes distants.

```read```
La commande read enregistre le texte saisi au clavier dans la variable indiquée en argument. Elle est utilisée dans les scripts interactifs afin d’enregistrer une information utilisable ultérieurement dans le script.

```rsync```
Cette commande permet de synchroniser les données d’un disque ou même d’un simple fichier avec le contenu d’un autre disque ou d’un autre fichier en réseau. Elle est similaire à rcp mais offre plus d’options.

```screen```
L’utilitaire GNU screen décline le terminal en cours en plusieurs virtuels, chacune exécutant ses propres commandes. Pour créer un nouveau terminal on entre screen -S suivi du nom du terminal virtuel en argument. Pour rebasculer sur le terminal principal, il suffit de taper ctrl+a puis d. Pour basculer vers un autre terminal virtuel, on tape screen -R suivi du nom du terminal.

```sdiff```
Les administrateurs utilisent sdiff pour comparer deux fichiers et produire une liste côte à côte indiquant les lignes qui sont dissemblables. La commande fusionne ensuite les fichiers et produit les résultats dans le fichier de sortie.

```sed```
L’utilitaire sed est un éditeur de flux, qui filtre/modifie un texte caractère par caractère, ce qui le distingue des autres éditeurs. Cette commande est généralement utilisée pour extraire une partie d’un fichier selon un motif, ou pour substituer plusieurs occurrences d’une chaîne dans un fichier.

```service```
Cette commande est le moyen le plus rapide de démarrer ou d’arrêter un service ; on l’utilise généralement pour les services réseau.

```shutdown```
La commande shutdown éteint l’ordinateur et peut être combinée avec des variables telles que -h pour signifier l’arrêt complet ou -r pour lancer un redémarrage.

```slocate```
Tout comme la commande locate, slocate - ou localisation sécurisée - permet d’indexer et de rechercher rapidement des fichiers, mais elle peut aussi cacher les informations sur les autorisations d’accès et la propriété des fichiers aux utilisateurs non autorisés.

```Snort```
Snort est un système de détection d’intrusions et un renifleur de paquets Open source qui surveille le trafic réseau. Il examine chaque paquet pour détecter les empreintes dangereuses ou les anomalies suspectes. Snort est basé sur libpcap.

```sort```
Cette commande permet de trier les lignes de texte par ordre alphabétique ou numérique en fonction des champs. Les utilisateurs peuvent saisir plusieurs clés de tri.

```sudo```
La commande sudo permet à certains utilisateurs d’exécuter certaines commandes comme s’ils étaient les administrateurs du système.

```SSH```
Secure Socket Shell (SSH) est une interface de commande pour l’accès sécurisé aux ordinateurs distants. Elle est utilisée par les administrateurs pour contrôler les serveurs à distance.

```tar```
La commande tar permet aux utilisateurs de créer des archives à partir d’un certain nombre de fichiers spécifiés ou d’extraire des fichiers d’une archive spécifique.

```tail```
La commande tail affiche les dernières lignes d’un fichier. Cela est particulièrement utile pour le dépannage du code, car les administrateurs n’ont pas souvent besoin de l’intégralité des logs pour déterminer les erreurs.

```TOP```
La commande top est utilisée pour afficher les processus Linux en cours d’exécution. Elle ouvre un mode interactif dont la partie supérieure contient les statistiques sur les processus et l’utilisation des ressources. Et la moitié inférieure contient une liste des processus en cours d’exécution. On quitte ce mode interactif en appuyant sur q.

```touch```
Les administrateurs peuvent créer un fichier vide dans Linux avec la commande touch.

```tr```
Cette commande permet de modifier ou de supprimer des caractères dans un flux de texte. Elle ne lit pas ces caractères en entrée depuis un fichier texte, mais depuis l’entrée standard et écrit aussi son résultat sur la sortie standard.

```traceroute```
La fonction traceroute détermine et enregistre un itinéraire sur Internet entre deux ordinateurs. Elle est utile pour résoudre les problèmes de réseau/routeur. Si le domaine ne fonctionne pas ou n’est pas disponible, les administrateurs peuvent utiliser traceroute pour tracer une IP.

```uname```
Cette fonction affiche le nom du système d’exploitation actuel et peut imprimer des informations sur le système.

```uniq```
Avec uniq, les administrateurs peuvent comparer les lignes adjacentes dans un fichier et supprimer ou identifier les lignes en double.

```vi```
L’environnement vi est un éditeur de texte qui fonctionne en utilisant uniquement le clavier.

```vmstat```
La commande vmstat prend un instantané de tout ce qui se trouve dans un système et rapporte des informations sur des éléments tels que les processus, la mémoire, la pagination et l’activité du processeur. C’est une bonne méthode que les administrateurs peuvent utiliser pour déterminer où des problèmes/ralentissements peuvent survenir dans un système.

```wget```
Il s’agit d’un utilitaire réseau qui récupère les fichiers web supportant les protocoles HTTP, HTTPS et FTP. La commande wget fonctionne de manière non interactive en arrière-plan lorsqu’un utilisateur est déconnecté. Elle peut créer des versions locales de sites web distants et recréer les répertoires de sites originaux.

```while```
Voir l’entrée for.

```whoami```
La commande whoami affiche le nom de l’utilisateur en cours.

```xargs```
Les administrateurs utilisent xargs pour lire, construire et exécuter des arguments à partir d’une entrée standard. Chaque entrée est séparée par des blancs.
