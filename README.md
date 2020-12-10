# project
“Talk To Me Nice” is an iOS app we designed with the purpose of translating spoken text from English to another language. 
The title bar and buttons are blue because we all decided that blue is a nice color.

To run this application, you will need to have successfully installed the flutter SDK (tutorial: https://flutter.dev/docs/get-started/install/macos) and 
Xcode (tutorial: https://www.freecodecamp.org/news/how-to-download-and-install-xcode/). Once they have been successfully installed, download the project 
zip file. Then, use the terminal to navigate to that project directory, then go to the directory named “talk_to_me_nice”. Once in that directory, type 
“open -a Simulator” (the iPhone simulator program that was downloaded alongside Xcode) in the terminal. Create a simulated device of an iPhone with an iOS
below 13.2.2. Finally, type “flutter run” in the terminal to run the project. If any errors occur, follow the directions provided in the terminal by the 
flutter. If for any reason this does not work, create your own flutter project by typing “flutter create our_project”. Then, replace the files “main.dart” 
(in our_project/lib/main.dart), “pubspec.yaml” (in our_project/pubspec.yaml), and “Info.plist” (in our_project/ios/Runner/Info.plist”) with talk_to_me_nice 
files of the the same name. Additionally, add talk_to_me_nice’s “languages.dart” file into the our_project/lib folder. Then, use the terminal to go to the 
our_project directory and run “open -a Simulator”, and then “flutter run”.

In the title bar, you will see the name of the app “Talk To Me Nice”, and next to that is a drop down menu of languages you can translate into. We got all 
these language options from Google Translate, so the 16 most common languages that are available in Google Translate are available and accessible in this
app. 

The main screen is white and has the message “Press the mic button and start speaking” displayed. This message disappears once you use the mic button to 
say a message for the app to translate. That message you spoke will then be displayed on the main screen for you to check and see what the app heard you say. 

At the bottom of the screen, you will see 5 buttons that all have different functions. We are going to go over the function of each button below, but in order 
to do that, each button will be numbered and talked about from left to right.

Translate button: This button has the icon with an “A” in the english language and another language. When you tap this button, it will translate the message 
spoken into the language that was selected from the drop down menu in the title bar.

Speak button: This button has the man icon speaking. When you tap this button, it will relay the message to you, the user. If the message has not been 
translated yet, once the button is pressed, it will relay the message to you back in English. If it has been translated, then once the button is pressed, 
it will only relay the translated version of the message to the user. 

Mic button: This button has a microphone icon on it. Once the button is pressed, it starts recording what you, the user, is saying and writes it as text on 
the main screen. In order to stop the mic from recording what you say, you must tap it again. 

Clear button: This button has an icon that has an arrow pointing backwards, with an “x” in it. This button, when pressed, will clear the message that the user 
recorded using the mic button. 

Image Translator button: This button has an icon that looks like a camera. When pressed, this button will open up your camera, once permission is allowed, so 
that you can take a picture or scan an image and it will take that text and put it on the main screen. That way you can have it on the main screen and decide 
if you want it read to you, or translated and then read to you. 

Link to youtube video: https://youtu.be/4vvgiqTqYjA
