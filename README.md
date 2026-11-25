# Ghost Infrastructure

Un logiciel pour Windows 10 et 11 qui comprend ton PC : il cartographie tes dossiers, projets, dépendances, applications et configurations, surveille les ressources, garde l'historique de tout ce qui change et te prévient des problèmes avant qu'ils arrivent. **Tout reste sur ton PC.**

## Ce qu'il fait

- **Mémoire des fichiers** : historique des créations, modifications, suppressions, déplacements et renommages ; doublons ; fichiers sans lien avec tes projets ; recherche dans les noms et le contenu.
- **Dépendances** : analyse des projets Node.js (npm, Yarn), Rust (Cargo) et Python (pip, Poetry, uv…) : dépendances directes et indirectes, versions incohérentes, environnements cassés.
- **Surveillance** : processeur, mémoire, disques, réseau et programmes, comparés aux habitudes de ton PC à la même heure.
- **Chronologie** : tout ce qui a changé, comparaison de deux périodes, évolution du disque, carte des relations à une date passée.
- **Diagnostics** : chaque problème avec ses preuves, son niveau de confiance, ses conséquences et des solutions.
- **Réparations** : toujours expliquées, confirmées par toi, sauvegardées avant et annulables (rien n'est supprimé définitivement, tout passe par la corbeille).
- **Carte interactive** des liens entre projets, dépendances, outils, applications et configurations.
- **Simulateur** : « que se passe-t-il si je mets à jour cette dépendance ? » — sans rien modifier.
- **Questions** : « Pourquoi mon stockage augmente-t-il ? », « Qu'est-ce qui a changé depuis hier ? »…

## Télécharger

👉 [**GhostInfrastructure-setup.exe**](https://github.com/ayusecour-stack/ghost-infrastructure/releases/latest/download/GhostInfrastructure-setup.exe) — installateur, sans droits administrateur.

Si Windows affiche « Windows a protégé votre ordinateur », clique sur **Informations complémentaires** puis **Exécuter quand même**.

Au premier lancement, choisis les dossiers à analyser. La surveillance apprend les habitudes du PC : les alertes deviennent précises après quelques jours.

## Confidentialité

- Aucune donnée ne quitte ton PC (une seule option en ligne, désactivée par défaut, n'envoie que des noms de paquets aux registres publics).
- Les fichiers sensibles (`.env`, clés, mots de passe) ne sont jamais lus.
- Aucune modification sans ta confirmation, jamais d'action administrateur.

Tous les logiciels d'Ayuha : https://ayuha-hub.pages.dev
