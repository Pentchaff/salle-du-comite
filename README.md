# Salle du comité

Web app installable (PWA) pour s'entraîner chaque jour à l'oral sur des situations de due diligence TMT : le partner qui te cuisine, l'exec summary en 90 s, le small talk, l'articulation.

- **Micro natif** : enregistrement dans le navigateur, encodé en WAV 16 kHz, pauses mesurées localement.
- **Coaching** : l'audio est envoyé à Gemini (niveau gratuit de Google AI Studio) qui transcrit mot pour mot, relance comme un partner et donne un seul fix.
- **Aucune clé dans le code** : la clé Gemini est saisie dans les réglages de l'app et stockée sur le téléphone (localStorage).
- **Données** : historique et profil de défauts restent sur l'appareil ; export/import pour passer d'un téléphone à l'autre ; bilan hebdo à coller dans Claude.

## Installer
1. Ouvrir l'URL GitHub Pages dans Chrome (Android) ou Safari (iPhone).
2. Android : menu ⋮ → « Installer l'application ». iPhone : Partager → « Sur l'écran d'accueil ».
3. Réglages → coller la clé Gemini → « Enregistrer et tester ».

## Confidentialité
Sur le niveau gratuit, Google peut utiliser les contenus envoyés pour améliorer ses modèles : n'utiliser que les cas fictifs de l'app. Les vrais deals et transcripts de calls restent dans Claude.
