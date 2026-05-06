# Azure AI Avatar Chat

A browser-based demo that combines Azure AI Speech talking avatars, speech recognition, text-to-speech, and Azure OpenAI streaming chat.

## What It Demonstrates

- Azure Speech talking avatar over WebRTC
- Browser microphone speech recognition
- Streaming Azure OpenAI chat completions
- Sentence-level text-to-speech playback through the avatar
- Optional typed chat and image prompt input

## Demo Files

```text
Basic chat.html     Main avatar + chat demo
Basic avatar.html   Minimal avatar speech demo
avatar.html         Original single-file avatar sample
js/chat.js          Chat/avatar integration logic
js/basic.js         Minimal avatar control logic
```

## Run Locally

Serve the folder from a local web server:

```powershell
python -m http.server 8080
```

Open:

```text
http://127.0.0.1:8080/Basic%20chat.html
```

Fill in the runtime configuration on the page:

- Azure Speech region
- Azure Speech resource key
- Azure OpenAI endpoint
- Azure OpenAI API key
- Azure OpenAI deployment name

Then select **Open Avatar Session**.
