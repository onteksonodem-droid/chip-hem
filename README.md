# Chip HEM — calculatrice de chip thinning

Calculatrice d'amincissement du copeau (RCTF) pour le fraisage HEM (faible engagement radial). Unités en pouces.

**Ouvrir l'app :** https://onteksonodem-droid.github.io/chip-hem/

## Installer sur un cellulaire
- **Android (Chrome)** : ouvrir le lien, menu ⋮ → « Ajouter à l'écran d'accueil » / « Installer l'application ».
- **iPhone (Safari)** : ouvrir le lien, bouton Partager → « Sur l'écran d'accueil ».

Une fois installée, l'app fonctionne sans réseau.

## Formules
- RCTF = D / (2·√(D·ae − ae²)) si ae < D/2, sinon 1
- fz programmée = copeau visé × RCTF
- RPM = SFM × 3.82 / D
- Avance = RPM × dents × fz programmée
- MRR = ae × ap × avance

Valeurs de départ : ajuster selon le fabricant de la fraise et la rigidité du montage.

## Mise à jour
Après toute modification des fichiers, changer la version du cache dans `sw.js` (`chip-hem-v1` → `chip-hem-v2`), sinon les cellulaires gardent l'ancienne version.
