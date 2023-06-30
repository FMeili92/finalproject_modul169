# ChatGPT Chatbot

Dieses Repository enthält den Code für einen ChatGPT-Chatbot, der feinabgestimmt wurde, um verbesserte Konversationsfähigkeiten bereitzustellen. Der Chatbot verwendet das OpenAI GPT-3.5-turbo-Modell, um menschenähnliche Antworten zu generieren.

## Anforderungen

Um den Chatbot auszuführen, stellen Sie sicher, dass Sie die folgenden Abhängigkeiten installiert haben:

- Node.js
- Firebase
- OpenAI API

## Installation

1. Klonen Sie dieses Repository auf Ihren lokalen Rechner.
2. Installieren Sie die erforderlichen Abhängigkeiten, indem Sie den folgenden Befehl ausführen:

```shell
npm install
```

3. Richten Sie eine Firebase-Echtzeitdatenbank ein und erhalten Sie den `apiKey` aus Ihrem Firebase-Projekt.
4. Erstellen Sie eine `.env`-Datei und fügen Sie die folgenden Umgebungsvariablen hinzu:

```
OPENAI_API_KEY=DEIN_OPENAI_API_SCHLÜSSEL
```

5. Ersetzen Sie `DEIN_OPENAI_API_SCHLÜSSEL` in der `.env`-Datei durch Ihren OpenAI-API-Schlüssel.
6. Initialisieren Sie die Firebase-App, indem Sie das `appSettings`-Objekt im Code mit der URL Ihrer Firebase-Datenbank anpassen.
7. Führen Sie den Chatbot mit dem folgenden Befehl aus:

```shell
npm start
```

## Verwendung

1. Öffnen Sie Ihren Browser und navigieren Sie zu `http://localhost:5173`.
2. Geben Sie Ihre Anfragen oder Nachrichten im Eingabefeld ein und drücken Sie die Eingabetaste.
3. Der Chatbot generiert Antworten basierend auf dem Verlauf des Gesprächs.
4. Klicken Sie auf die Schaltfläche "Clear", um das Gespräch zurückzusetzen und ein neues zu beginnen.

## Beitrag

Beiträge zu diesem Projekt sind willkommen. Bitte reichen Sie Probleme und Pull Requests ein, um die Funktionalität und Leistung des Chatbots zu verbessern.


## Danksagungen

Dieses Projekt nutzt folgende Technologien und Bibliotheken:

- Firebase
- OpenAI API
- Node.js

Ein besonderer Dank gilt OpenAI für die Bereitstellung des leistungsstarken GPT-3.5-turbo-Modells.
