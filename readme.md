# Speech Synthesis Demo

This project provides a simple form that allows the user to convert text to 
speech via the speech synthesis browser API. It also provides some controls for pitch, rate and voice.

[See the demo here](https://rjbultitude.github.io/Web-SpeechSynthesis-demo/)

## Dependencies
None

## Dev Dependencies
HTTP server, to run the project in browser

## Notes and plans
* This demo uses native ES modules, so [browser support will be mixed](https://caniuse.com/#search=modules)
* Add min-max ranges to `rate` and `pitch`
* Make `loadVoices` Promise based

## Credits and references
[Using the speech synthesis interface](https://manu.ninja/using-the-speech-synthesis-interface-of-the-web-speech-api/)
