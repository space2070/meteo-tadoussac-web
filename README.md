# Marées Tadoussac

Dashboard temps réel des marées de Tadoussac (Québec) — page statique sans dépendance.

- Scène peinte vivante : trois tableaux animés en boucle (nuit, heure dorée, jour — images Gemini/Nano Banana, animation Veo/Flow) fondus selon la vraie position du soleil à Tadoussac ; bélugas, goélands et deux chiens sur la rive
- Niveau d'eau en direct (interpolé à la seconde), voile de marée qui monte et descend avec la vraie marée
- Courbe de la journée, marées du jour, prévisions 7 jours
- Données : prédictions officielles du Service hydrographique du Canada, station Tadoussac 03425, via l'[API publique IWLS](https://api-iwls.dfo-mpo.gc.ca/swagger-ui/index.html) de Pêches et Océans Canada
- Un seul fichier `index.html` — HTML/CSS/JS vanilla, hébergé sur GitHub Pages
