# Vayvi Privacy

Dépôt public de la politique de confidentialité de **Vayvi**, application Android publiée sous le nom **GolApp Studio**.

## Politique publique

https://shamsgolap.github.io/vayvi-privacy/

## Documents publics

- Politique de confidentialité : `index.md`.
- Conditions générales d’utilisation (bêta gratuite) : `cgu.md`, [page publique](https://shamsgolap.github.io/vayvi-privacy/cgu.html).

Une modification importante doit être reportée dans le contenu hors ligne de Vayvi (`terms_of_use_content.dart`). Les CGU ne remplacent pas des mentions légales complètes ni les futures CGV de Vayvi+.

## Fichier principal

La politique publiée est maintenue dans `index.md`.

La ligne :

```text
Version concernée : Vayvi X.Y.Z+N
```

sert également de source à la page publique du programme de test Vayvi pour afficher automatiquement la version courante.

## Maintenance

Lorsqu'une version de Vayvi modifie les pratiques de données, les SDK, la publicité, les permissions, le partage ou les mécanismes de suppression :

1. vérifier les pratiques techniques réelles de l'application ;
2. mettre à jour `index.md` avant la diffusion ;
3. mettre à jour la date de la politique si le contenu change de manière significative ;
4. vérifier la cohérence avec les déclarations Google Play ;
5. vérifier que le site GitHub Pages se déploie correctement.

## Sécurité

Ce dépôt est public. Ne jamais y publier de secret, clé de signature, token, fichier `.env`, identifiant de compte de service ou donnée personnelle inutile.

Voir [SECURITY.md](SECURITY.md).

## Contact

golappstudio.support@gmail.com

## Synchronisation Vayvi 0.4 (17 novembre 2026)

- Source de vérité fonctionnelle : `ShamsGolap/vayvi`, branche `develop` (candidate `0.4.0+8`). Les nouvelles langues de `experiment/global` ne sont pas des fonctionnalités publiées.
- La ligne `Version concernée : Vayvi 0.3.0+7` désigne volontairement l'APK réellement proposée sur Google Play en test fermé ; **ne pas l'incrémenter** à 0.4 avant publication Play vérifiée, car `vayvi-testing/version-sync.js` la lit.
- La candidate 0.4 prévoit : 5 évaluations Free, 2 suivis actifs, 4 points par relation / 30 jours, offres Vayvi+ via RevenueCat et données de personnalisation stockées localement.
- La Preview utilise des annonces de test et le RevenueCat Test Store (paiements fictifs). Aucun achat réel ne doit être annoncé avant validation Google Play du compte marchand, des produits et des tests.
- L'application hors ligne embarque aussi des CGU (`app/lib/features/about/presentation/terms_of_use_content.dart`) : contrôler leur alignement avec les CGU publiques avant de publier la nouvelle version de l'application. Les documents de ce dépôt ne suffisent pas à valider juridiquement la monétisation.
- Vérifier les formulaires Play Console « Sécurité des données », le manifeste final, les déclarations du SDK RevenueCat et les informations d'identité légale avant mise en production.
