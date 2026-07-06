# Marées Tadoussac

Dashboard temps réel des marées de Tadoussac (Québec) — page statique sans dépendance.

- Scène peinte vivante : trois tableaux animés en boucle (nuit, heure dorée, jour — images Gemini/Nano Banana, animation Veo/Flow) fondus selon la vraie position du soleil à Tadoussac ; bélugas, goélands et deux chiens sur la rive
- Almanach imprimé sous la scène : niveau d'eau en direct (interpolé à la seconde) avec jauge basse→haute, deux encres sémantiques validées daltonisme (bleu = marée haute, ambre = basse)
- Courbe de la journée avec heures de nuit ombrées et échelle en mètres, registre des marées du jour (prochaine mise en évidence), semaine avec mini-courbes par jour
- Données : prédictions officielles du Service hydrographique du Canada, station Tadoussac 03425, via l'[API publique IWLS](https://api-iwls.dfo-mpo.gc.ca/swagger-ui/index.html) de Pêches et Océans Canada
- Un seul fichier `index.html` — HTML/CSS/JS vanilla, hébergé sur GitHub Pages
