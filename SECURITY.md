# Sécurité

Ce dépôt est public et sert à publier la politique de confidentialité de Vayvi.

## Ne jamais publier ici

- mots de passe ;
- tokens GitHub ou clés API ;
- fichiers `.env` réels ;
- clés de signature Android (`.jks`, `.keystore`) ;
- clés privées ou certificats contenant une clé privée ;
- identifiants de comptes de service ;
- exports ou captures contenant des données personnelles inutiles.

Le fichier `.gitignore` bloque plusieurs formats courants, mais il ne remplace pas une vérification avant chaque commit.

## En cas de secret publié par erreur

1. révoquer ou faire tourner immédiatement le secret concerné ;
2. ne pas considérer sa simple suppression dans un nouveau commit comme suffisante ;
3. nettoyer l'historique Git si nécessaire ;
4. vérifier les journaux et accès associés au secret.

## Signaler un problème de sécurité

Pour un problème de sécurité concernant Vayvi, ce site ou cette politique :

**golappstudio.support@gmail.com**

Évite de publier publiquement dans une issue GitHub des informations privées, des captures sensibles ou des données concernant une autre personne.
