Epic Games :
Appel direct à l'API officielle freeGamesPromotions — donc pas de fake, tu as les jeux gratuits de cette semaine + la date de fin + les prochains jeux mystères
Image large, prix barré, bouton qui t'envoie sur la page Epic

Steam 100% :
J'essaie de scanner l'API featuredcategories pour les promos à 100% (final_price = 0)
Comme Valve n'a pas d'API officielle pour les "gratuits à vie", j'ai mis un fallback avec les derniers connus + un bandeau explicatif. Si l'API renvoie rien, tu vois quand même les jeux.
Fonctionnalités intégrées :

Compte à rebours live "Se termine dans 2j 5h"
Bouton "Je l'ai récupéré" sauvegardé en local
Recherche + onglets Epic / Steam
Design glassmorphism, responsive
