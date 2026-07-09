# Image-Analysis_Open-Desk
Opendesk in image analysis @ I2BC

🔧 Comment utiliser la date manuelle ?
Ouvrez le fichier HTML et cherchez cette ligne (vers la fin, dans la balise <script>) :

const manualDate = null; // Exemple : '2026-07-16'

Pour forcer une date : Remplacez null par une date au format 'AAAA-MM-JJ' (ex: '2026-07-23').
Pour revenir au mode automatique : Remettez null.

Exemple concret

Si vous mettez const manualDate = '2026-07-23'; et que nous sommes avant le 23 juillet → la date du 23 juillet s’affichera.
Si le 23 juillet est passé → le prochain mercredi sera affiché.

