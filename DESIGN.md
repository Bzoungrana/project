In our project “Talk To Me Nice”, we used the flutter framework and the dart language to create a translator app that has 5 buttons on the bottom where, from
left to right, we have: a translating button, a dictating button, a microphone button in which the app can receive audio input, a clear button, and a button
that will toggle the user’s camera to allow scanning of text.

In order to take audio input, we used flutter’s speech_to_text package to detect user audio input and display what was said. We then used HTTP POST to send the
text to an API we built which then sent the text to a google translate library that returned to us the translated text.

To build the API, we switched to node.JS because the python translation library was crashing for an unknown reason. With node.JS, we used a framework called
express to create a simple web application. The web application had one primary POST function which accepted a JSON object with two values, being text and
language. The web application used a google translate library in node.JS to translate the given text into the desired language. It then returned the translation
to the client.

To allow dictation of text, we used a flutter package called text_to_speech which allowed us to dictate a given text in relevant language accents.

To create the clear button we simply deleted the text and displayed a default message: “Press the mic button and start speaking”

We attempted to facilitate the use of the camera button but were unable to test its functionality so we decided to render it useless.

All of the code we wrote is located in 3 files: "main.dart", "languages.dart", and "server.js"
