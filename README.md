# Whisper Transcription Tool

Outil de transcription automatique de vidéos et audio utilisant OpenAI Whisper.

## Fonctionnalités

- 🎥 **Transcription de vidéos YouTube** via URL
- 📁 **Traitement par lot** de dossiers de fichiers
- 🎵 **Support des fichiers audio** (MP3, WAV, AAC, FLAC, OGG, M4A)
- 🎬 **Support des fichiers vidéo** (MP4, AVI, MKV, WebM, MOV, FLV)
- 📝 **Export en format texte** (.txt) et sous-titres (.srt)
- 🔄 **Versioning GitHub** pour suivi des modifications

## Structure du projet

```
whisper-transcription-tool/
├── notebooks/
│   ├── transcription_v1_legacy.ipynb    # Version originale
│   └── transcription_v2_refactored.ipynb # Version améliorée (à venir)
├── README.md
├── requirements.txt
└── CHANGELOG.md
```

## Installation

```bash
pip install -r requirements.txt
```

## Utilisation

1. Ouvrir le notebook dans Jupyter ou Kaggle
2. Exécuter les cellules d'installation
3. Choisir le type de source (URL, dossier, fichier unique)
4. Lancer la transcription

## Versions

- **v1.0-legacy**: Version originale avec gestion GPU complexe
- **v2.0** (à venir): Version refactorisée et simplifiée

## Contribution

Ce projet utilise le versioning Git pour tracker les améliorations. Chaque modification majeure est taguée pour permettre les roll-backs.

## Licence

MIT License
