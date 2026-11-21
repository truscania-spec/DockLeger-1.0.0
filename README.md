Dock Léger 1.0.0 — par christ13430 (licence MIT)
==================================================

Un dock de lancement façon RocketDock, écrit en Rust natif Windows :
un seul .exe de 58 Ko, aucun runtime, aucune installation obligatoire.

VERSION PORTABLE (ce dossier)
  • Double-cliquez sur DockLeger.exe. Le dock apparaît en bas de l'écran.
  • Les réglages sont enregistrés dans dock.ini, à côté de l'exe :
    placez ce dossier où vous voulez (clé USB, Documents…), pas dans
    « Program Files » (dossier protégé en écriture).

UTILISATION
  • Ajouter : glissez des programmes, raccourcis, dossiers ou fichiers sur le dock
    (ou clic droit › Ajouter un programme…).
  • Lancer : clic sur une icône.
  • Réorganiser : maintenez le clic sur une icône et glissez-la.
  • Clic droit : retirer, ouvrir l'emplacement, position haut/bas, taille des icônes,
    premier plan, démarrage avec Windows, English, À propos (affiche la mémoire utilisée), Quitter.

MÉMOIRE
  Le dock rend sa mémoire inutilisée à Windows dès que la souris le quitte.
  Il ne consomme du processeur que pendant l'animation de survol.

ENGLISH
  Right-click the dock › English to switch the interface to English.

Windows 10 / 11 (64 bits). Windows SmartScreen peut avertir au premier lancement
car l'exe n'est pas signé : « Informations complémentaires » › « Exécuter quand même ».
