# n8n Agent IA - FAQ Assistant Workflow

Ce repository contient un workflow **n8n** permettant de créer un assistant IA FAQ qui répond automatiquement aux messages Telegram en utilisant Google Gemini et d'autres outils d'IA.

## Fonctionnalités

- Réception des messages Telegram via le trigger `Telegram Trigger`.
- Traitement des messages texte et vocaux.
- Utilisation de Google Gemini (PaLM) pour générer des réponses en texte ou en audio selon votre message.
- Lecture et extraction de documents Google Docs pour fournir des réponses précises.
- Envoi de réponses sur Telegram sous forme de texte ou audio.

## Prérequis

- n8n v3 ou plus récent
- Node.js v20
- Clé API Telegram Bot
- Clé API Google Docs OU File ID
- Clé API Google PaLM (Gemini)
- Clé API ElevenLabs (optionnel pour TTS)

## Installation et utilisation

1. Cloner le repository :  
   ```bash
   git clone https://github.com/TON_UTILISATEUR/n8n-agentIA-FAQ-assistant-workflow.git
   cd n8n-agentIA-FAQ-assistant-workflow
