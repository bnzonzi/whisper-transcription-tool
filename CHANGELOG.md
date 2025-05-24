# Changelog

Toutes les modifications notables de ce projet seront documentées dans ce fichier.

## [v1.0-legacy] - 2025-05-24

### Initial Release
- ✅ Version originale du notebook de transcription
- ✅ Support pour transcription de vidéos YouTube
- ✅ Support pour traitement par lot de fichiers vidéo
- ✅ Gestion complexe du GPU (à simplifier)
- ✅ Export en formats .txt et .srt
- ✅ Integration Hugging Face Hub

### Issues identifiées
- ❌ Gestion GPU complexe et non fonctionnelle
- ❌ Code redondant et commenté
- ❌ Erreurs d'encodage dans les chaînes
- ❌ Variables non définies dans la seconde partie
- ❌ Interface utilisateur peu intuitive

## [v2.0] - 2025-05-24

### New Features
- ✅ Interface utilisateur simplifiée avec choix de source
- ✅ Support natif des fichiers audio (MP3, WAV, AAC, FLAC, OGG, M4A)
- ✅ Détection automatique du type de fichier (audio/vidéo)
- ✅ Workflow unifié pour traitement audio et vidéo
- ✅ Gestion automatique du GPU avec fallback CPU
- ✅ Interface claire avec emojis et messages informatifs

### Improvements
- ✅ Code complètement refactorisé et organisé en cellules logiques
- ✅ Suppression de la gestion GPU complexe et non fonctionnelle
- ✅ Correction des erreurs d'encodage (\\n → \n)
- ✅ Suppression du code redondant et commenté
- ✅ Variables de configuration centralisées
- ✅ Gestion d'erreurs améliorée
- ✅ Documentation intégrée avec markdown

### Breaking Changes
- ❗ Suppression de la gestion multi-GPU complexe
- ❗ Suppression de l'interface input() remplacée par variables
- ❗ Restructuration complète du code legacy
