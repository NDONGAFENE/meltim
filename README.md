# MELTIM V2.1 — Application de bureau (.exe)

Développé par **Pro-Technologie**

Gestion scolaire (lycée & collège) : élèves, enseignants, classes & matières,
notes & bulletins, présences, espace de partage (devoirs & exercices), échanges
enseignants ↔ direction. Rôles : Direction (accès total), Secrétariat, Enseignant,
Élève. Licence par clé `ML-`.

## Construire l'installateur (.exe)

Prérequis : **Node.js** (nodejs.org).

1. Ouvrez `cmd` dans ce dossier (barre d'adresse → cmd).
2. `npm install` puis `npm run dist`.
3. L'installateur **« MELTIM Setup 2.1.0.exe »** apparaît dans `dist`.

## Premier usage

- Connexion de départ : **admin** / **admin** (à changer dans Paramètres).
- Choix du mode au démarrage : **Poste unique** (le portail réseau viendra ensuite).
- Renseignez l'établissement (Paramètres), créez classes, matières, élèves,
  enseignants, puis les comptes (Utilisateurs).
- Essai 30 jours, puis clé de licence (préfixe `ML-`) via l'onglet Licence.

## Générer une clé de licence

Onglet **Licence** → **Ouvrir le générateur** → mot de passe du générateur →
type (Essai / Durée / Illimitée) + durée → **Générer** → **Copier**.

## Comptes & rôles

La Direction crée les comptes dans **Utilisateurs**. Un compte **Élève** se relie
à la fiche de l'élève (il voit alors les devoirs de sa classe et ses notes).

## IMPORTANT — confidentialité

Les valeurs du générateur de licence et la phrase de signature sont confidentielles.
Effectuez des sauvegardes régulières (Paramètres → Sauvegarde).
