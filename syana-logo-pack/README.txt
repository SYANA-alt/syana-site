SYANA — Pack Logo (palmier) — prêt à installer
===============================================

Ce pack contient :
- assets/images/logo/syana-logo.png  → le logo (fond transparent)
- logo-snippet.html                  → le bloc HTML à coller dans votre en-tête
- instructions ci‑dessous

Installation (2 étapes) :
1) Décompressez l’archive à la RACINE du projet (dossier syana-site).
   → vous devez obtenir le chemin : syana-site/assets/images/logo/syana-logo.png

2) Ouvrez index.html et remplacez le contenu du bloc du logo par le snippet :
   - Recherchez dans <header> le lien du logo : <a class="brand" ...> ... </a>
   - Supprimez l’ancien contenu interne (SVG, <span class="word">...</span>, etc.)
   - Collez le contenu de 'logo-snippet.html' à la place (entre <a class="brand"> et </a>)

   Snippet (rappel) :
<!-- Logo SYANA (image) -->
<a class="brand" href="/" aria-label="Accueil">
  <img
    src="/assets/images/logo/syana-logo.png"
    alt="SYANA Conciergerie — Côte d’Azur"
    width="220"
    height="auto"
    loading="eager"
    decoding="async"
    style="display:block"
  />
</a>


Sauvegardez puis publiez (GitHub Desktop → Commit → Push origin).
Vérifiez l’image en direct : /assets/images/logo/syana-logo.png

Pack généré le 2025-09-13 18:33:45.
