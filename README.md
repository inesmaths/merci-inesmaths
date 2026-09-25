Page de remerciement inesmaths.fr (après inscription pour recevoir les fiches)

Contenu :
- merci.html : la page complète (HTML + CSS + JS, aucune dépendance sauf Google Fonts Poppins / Dancing Script)
- ines.jpg : photo ronde du bloc promo
- fiches/f01.jpg à f30.jpg : les fiches qui défilent en fond

Pour Shopify :
1. Déposer ines.jpg et les 30 fiches dans Contenu > Fichiers.
2. Remplacer les chemins "ines.jpg" et "fiches/fXX.jpg" par les URL du CDN Shopify
   (le tableau des fiches est construit dans le <script> en bas de page, variable "fiches").
3. Créer une page /merci (template sans header/footer de préférence) avec ce code.
4. Code promo MERCI30 (-30 %) à créer dans Shopify > Réductions s'il n'existe pas.
5. Le bouton "Découvrir les fiches" pointe vers https://www.inesmaths.fr.

Pour voir la page : ouvrir merci.html dans un navigateur, en laissant le dossier fiches/ à côté.
