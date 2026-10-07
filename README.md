# Guide Quiz Vélo en Retz

Application du parcours Les Moutiers-en-Retz → La Bernerie-en-Retz → Pornic.

- 5 arrêts × 5 questions.
- Le guide lance chaque arrêt manuellement.
- Un seul scan du QR code par joueur.
- Session et points conservés entre les arrêts.
- Réponses QCM/Vrai-Faux mélangées automatiquement à chaque lancement.
- Interface joueur séparée de l’interface guide.

## Photos
Chaque étape du parcours possède maintenant une photo locale dans `assets/` :

- Lanterne des morts : `assets/lanterne-morts.jpg`
- La Tenue de Mareil : `assets/tenue-mareil.jpg`
- Plan d’eau Maurice-Giros : `assets/plan-eau-maurice-giros.webp`
- La Rogère : `assets/la-rogere.jpg`
- Château de Pornic : `assets/chateau-pornic.jpg`

Sources et crédits : Wikimedia Commons pour la lanterne et le château ; IntraMuros / La Tenue de Mareil pour la saline ; GO Challans GOis, photo Mélanie Chaigneau, pour le plan d’eau Maurice-Giros.
Les photos sont stockées dans le dépôt afin de fonctionner aussi sur téléphone et via QR code.

## Déploiement
`index.html` doit rester à la racine. Compatible Netlify et GitHub Pages.
