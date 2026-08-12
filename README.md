Demo page for exploring [Web Speech API](https://webaudio.github.io/web-speech-api) timestamps and latency.

See the [explainer](https://github.com/WebAudio/web-speech-api/blob/main/explainers/speech-recognition-result-timestamps.md), [Issue #191](https://github.com/WebAudio/web-speech-api/issues/191) and [ChromeStatus](http://chromestatus/5811907077472256) for more information about the proposed `SpeechRecognitionResult` WebIDL attributes: `audioStartTime` and `audioEndTime`.

Run the latest demo [HERE](https://michaelwasserman.github.io/web-speech-demos/speech_latency.html) and use `--enable-blink-features=WebSpeechTimestamps` to test the new timestamp attributes in Chrome.
