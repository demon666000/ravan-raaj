# SarvAI V3 — Android-friendly All-Rounder AI

SarvAI V3 is a mobile-first browser AI prototype designed to work on Android phones even when the local WebGPU model cannot load.

## What changed
- Local WebLLM model remains the first choice when the phone/browser supports WebGPU.
- Automatic cloud fallback through Puter.js when local AI fails.
- Uses a cloud AI model without putting an API key in the GitHub page.
- Voice input (where the browser supports SpeechRecognition).
- Text-to-speech for the latest answer.
- Basic text/code file reading for attached files.
- Local browser memory.
- Calculator for simple arithmetic.
- Safety layer for dangerous topics.

## Important about "every Android"
No web app can honestly guarantee every Android phone/browser. Very old browsers may not support modern JavaScript, WebGPU, speech recognition, or the cloud provider. V3 is designed to degrade gracefully: if local AI fails, it tries the cloud AI path.

## Puter note
Puter.js documents a keyless, serverless User-Pays model. The developer does not have to manage an AI API key or backend; users authenticate with Puter and their usage is covered by their Puter resources/plan. This is not a guarantee of unlimited free end-user usage.

## Safety
SarvAI can discuss dangerous subjects for education and safety, but it should not provide operational instructions for making/using weapons, poisons, dangerous chemicals, drugs, or other harmful activities. It can instead provide risks, prevention, emergency response, history, and high-level explanations.

## GitHub Pages
Upload/replace `index.html` in the existing `sarvai` repository and keep GitHub Pages on `main` / root.
