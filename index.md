# Politique de confidentialité de Vayvi

**Dernière mise à jour : 2 octobre 2026**

Version concernée : Vayvi 0.2.2+5, Android `com.golappstudio.vayvi`.

## Éditeur et contact

Vayvi est une application publiée sous le nom **GolApp Studio**.

Exploitant actuel : **SHAMS GOLAP**, personne physique publiant sous le nom GolApp Studio.

Contact confidentialité et support : **golappstudio.support@gmail.com**

Politique de confidentialité publique :
https://shamsgolap.github.io/vayvi-privacy/

## Ce que tu saisis

Tu peux saisir le nom ou surnom d'une personne et sélectionner des Green Flags,
Red Flags et Signaux majeurs. Vayvi conserve aussi un identifiant local
d'évaluation et ses dates. Un brouillon mémorise ta progression pour reprendre
plus tard. Analyse peut conserver des points successifs et ton ressenti ; Décide
peut conserver tes intentions et notes facultatives. Moi conserve ton profil
personnel et son brouillon lorsque tu utilises ces fonctions.

Ces informations servent à afficher tes évaluations, calculer leur score et
permettre leur consultation, modification ou suppression.

Le résultat repose sur tes choix : ce n'est pas un diagnostic scientifique,
médical ou psychologique, ni une vérité objective sur une personne.

Préfère un surnom et évite les informations personnelles inutiles sur d'autres
personnes.

## Stockage et absence de collecte par l'éditeur

Vayvi enregistre ces données dans une base locale, dans
l'espace de l'application sur ton appareil.

Dans cette version, l'application ne transmet pas les données relationnelles
à GolApp Studio et ne les fournit pas explicitement aux requêtes publicitaires.
Elle ne possède ni compte utilisateur, ni backend
applicatif, ni synchronisation cloud, ni sauvegarde serveur Vayvi.

GolApp Studio ne vend ni ne partage les données contenues dans tes évaluations.

Les sauvegardes, restaurations et transferts proposés par Android ou le fabricant
de ton appareil sont distincts de Vayvi. Selon ton appareil et tes réglages, ils
peuvent inclure les données de l'application, y compris dans une sauvegarde
distante. Vayvi ne les désactive pas explicitement dans cette version et
GolApp Studio n'y a pas accès.

Consulte les réglages et les informations de confidentialité de ces services pour
gérer leurs mécanismes de sauvegarde.

## Publicité, mesure d'audience et permissions

Sur Android, Vayvi Free peut afficher des annonces réelles : une bannière sur
les racines Analyse et Décide, dans un seul emplacement partagé au-dessus de la
navigation. Elle est absente sur Évalue, Moi et Résultat, ainsi que sur les routes
poussées au-dessus du shell, notamment les détails, formulaires et Paramètres.

Un interstitiel peut apparaître seulement après une évaluation finalisée, via
le CTA volontaire « Retour à l’accueil » depuis Résultat. La première
finalisation ne déclenche aucun interstitiel. L'éligibilité commence à partir de
deux finalisations depuis le dernier affichage confirmé. Avant le premier
affichage, aucun délai initial n'est imposé une fois ces deux finalisations
atteintes. Après chaque affichage confirmé par le SDK, le compteur revient à
zéro et un délai de 10 minutes s'applique avant un autre affichage. Le maximum
est de deux affichages confirmés par session/processus. Un échec de chargement
ou d'affichage ne consomme ni le compteur ni ce quota. Une annonce non prête
laisse la navigation fonctionner normalement, sans jamais la bloquer ; sa
disponibilité n'est pas garantie. Aucun interstitiel sur Back, Modifier, au
lancement, au retour au premier plan ou pendant un formulaire. L'autorisation de
demander des annonces dépend du statut retourné par UMP.
Vayvi+ bloque les annonces dans le fonctionnement normal.

Les builds de développement debug/profile utilisent par défaut les unités
officielles Google de test ; les builds release utilisent par défaut les unités
Vayvi de production. Une configuration explicite peut remplacer ce choix.
Le mode QA publicitaire utilise uniquement les unités Google de test et peut
permettre leur affichage indépendamment du statut Vayvi+.

Google Mobile Ads et UMP sont intégrés. Des communications réseau avec Google
peuvent avoir lieu pour déterminer et recueillir tes choix de consentement et
pour le fonctionnement, la diffusion et la mesure des annonces ainsi que la
prévention de fraude. Selon la configuration et le consentement
applicables, Google peut traiter des informations techniques telles que des
informations réseau et appareil, des identifiants publicitaires lorsqu'ils
sont disponibles, des interactions et des diagnostics. Le manifeste Android
inclut également des permissions AD_SERVICES : Android peut ainsi exposer au
SDK les API publicitaires Privacy Sandbox correspondantes. La présence d'une
permission ne prouve pas qu'une donnée est disponible ou collectée dans tous
les cas. Cette politique ne fixe pas de durée de conservation des données
techniques traitées par Google.

Aucune publicité récompensée réelle n’est utilisée.
Vayvi ne fournit explicitement aux requêtes publicitaires aucun nom ou surnom,
identifiant d'évaluation ou d'histoire, Flag,
Signal majeur, score, phase relationnelle, snapshot, décision, note ou donnée
de Moi et ne crée aucun profil publicitaire maison. Aucun Firebase Analytics
ni Google Analytics applicatif n'est intégré ; cela n'exclut pas les mesures
propres au SDK publicitaire. Lorsque UMP le requiert, « Options de
confidentialité » peut être rouvert dans Paramètres.

Vayvi+ reste une simulation entièrement locale, sans paiement réel.
Tous les Signaux majeurs sont gratuits, sans déblocage ni publicité récompensée.

La version Android release comprend les permissions biométriques nécessaires
au système et à la compatibilité des appareils. Le rappel quotidien pour Moi
est désactivé par défaut : tu peux l'activer explicitement et choisir son heure,
enregistrée localement. Android peut alors demander l'autorisation Notifications.
Le rappel utilise les notifications locales de l'appareil ; son contenu ne
contient aucun nom, score, Flag, Signal majeur ou donnée relationnelle. Une
permission de redémarrage permet de rétablir le rappel après redémarrage de
l'appareil. Le SDK publicitaire peut nécessiter un accès réseau. Vayvi ne demande pas d'accès à la caméra, au microphone,
aux contacts, à la localisation ou au stockage partagé.

Vayvi reçoit uniquement le résultat de l'authentification fourni par le système.
L'application ne reçoit ni ne stocke tes données biométriques.

## Partage

Le partage d'une carte est volontaire.

La carte est anonyme par défaut. Le nom ou surnom de la personne évaluée n'est
inclus que si tu choisis explicitement de l'ajouter.

La carte est générée localement dans le cache de Vayvi puis transmise à
l'application que tu choisis via les mécanismes de partage Android.

Une fois partagée, l'image quitte le contrôle de Vayvi. L'application destinataire
et les personnes auxquelles tu la transmets peuvent la conserver ou la
redistribuer.

Vérifie son contenu avant de la diffuser et évite de partager des informations
personnelles ou sensibles sans nécessité.

## Conservation et suppression

Les évaluations restent disponibles localement jusqu'à leur suppression. Il
n'existe pas de durée d'expiration automatique.

Le brouillon peut être remplacé ou effacé au fil de ton utilisation.

Tu peux supprimer individuellement une évaluation depuis son écran de détail,
après confirmation.

Dans Paramètres, l'action **« Supprimer toutes mes données »** efface notamment :

- les évaluations ;
- le brouillon ;
- les histoires suivies, leurs points et décisions ;
- le profil personnel et son brouillon ;
- les préférences locales de Vayvi ;
- les états locaux simulés ;
- le cache des cartes de partage.

Cette action efface les données locales prises en charge ci-dessus, pas toutes
les données liées aux services publicitaires. Elle ne réinitialise pas
automatiquement les choix UMP et n'efface pas le compteur technique local de
fréquence publicitaire. Elle ne supprime pas des données éventuellement détenues
par Google. Les choix publicitaires se gèrent via « Options de confidentialité »
lorsque UMP le requiert.

Si l'effacement du cache de partage
échoue après celui des données principales, l'application le signale et permet
de réessayer ; la vérification physique de ce parcours reste en attente.

Tu peux également utiliser l'effacement des données de l'application proposé par
Android ou désinstaller Vayvi.

Une désinstallation supprime normalement la copie locale présente dans
l'application. Les éventuelles copies ou restaurations gérées par le système
d'exploitation ou le fabricant dépendent de leurs propres réglages de sauvegarde.

GolApp Studio ne peut pas effacer à distance des données qu'il ne reçoit pas.

Aucun compte utilisateur n'existe dans cette version : il n'existe donc pas de
procédure de suppression de compte Vayvi.

## Sécurité

Vayvi utilise l'espace de stockage interne isolé fourni par Android.

Dans cette version, la base de données locale ne bénéficie pas d'un chiffrement
applicatif supplémentaire.

La protection biométrique optionnelle contrôle l'accès aux zones privées pendant
une session. Elle est désactivée par défaut et ne chiffre
pas la base de données locale.

L'absence de noms et de scores sur l'écran d'accueil limite également leur
exposition visuelle.

Protège ton appareil avec un mécanisme de verrouillage adapté et maîtrise les
options de sauvegarde de ton système.

Aucun système informatique ne peut garantir une sécurité absolue ou la
suppression forensique de toute trace.

## Public et mineurs

Vayvi est destiné aux personnes âgées de **18 ans et plus**.

L'application n'est pas conçue pour les enfants.

Utilise Vayvi dans un cadre de réflexion personnelle, avec respect pour les
personnes concernées, et ne considère pas ses scores ou interprétations comme une
vérité objective ou un diagnostic sur une personne.

## Évolution de cette politique

Cette politique pourra évoluer si les fonctionnalités ou les pratiques de Vayvi
changent.

Elle devra notamment être réévaluée avant l'ajout éventuel de fonctionnalités
telles que :

- nouveaux formats publicitaires ou changements de traitements publicitaires ;
- achats ou abonnements ;
- nouveaux services réseau ;
- analytics applicatif ;
- crash reporting ;
- synchronisation distante ;
- autres SDK susceptibles de traiter des données.

La date indiquée en haut de cette page sera mise à jour lors de toute modification
significative.

## Contact

Pour toute question relative à Vayvi ou à cette politique de confidentialité :

**GolApp Studio**
**golappstudio.support@gmail.com**

N'envoie pas d'évaluations, de captures contenant des informations privées ou de
données personnelles concernant d'autres personnes dans une demande de support.
