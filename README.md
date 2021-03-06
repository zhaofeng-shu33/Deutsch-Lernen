# Deutsch-Lernen
Complete description of the project can be found under manual/Introduction.pdf.
We aim to develop an user-oriented German learning software, whose features include but not limit to dictionary and translator, for students in China who learn German as a second foreign language in university.       
Wir wollen eine Software, die als ein Wörterbuch oder ein Übersetzer funktionieren kann, für die Chinisischen Studentinen und Studenten um ihren Universitätlernen zu helfen machen.       
この項目の目標は、大学生にドイツ語の勉強を手伝するソフトウェアを作る。

# Requirement
* Chrome or Firefox browser<br>
* Adding new words requires familiarity with xml syntax

# How to build
Clone this project and click index.html, you are done!<br>
If you have latex installed on your operating system, then you can open manual/Introduction.dtx in an editor and typesetting the file with "xelatex".
As a result, you will get the document Introduction.pdf and other generated codes link NounModel.dtd in the same directory.<br>
# Current Usage
You can locally maintain a small dictionary based on html-xml-js framework. However, adding new words by scraching xml codes is annoying, so we are managing to develop server side codes with Django to automate this process. The server side codes use all the client sides resources and can be found at https://github.com/zhaofeng-shu33/DeutschLernen_server.

# Process
Currently, we have finished client side code using jquery and halfly server side code with Django.
We also develop a Chrome extension application which can help web readers to search german words quickly.
First you need enable the extension, then on the addressbar(Shortcut: CTRL+L) type "de" plus a "Space" to enter search word mode, and search the german words as you link.
![screenshot](/images/screenshot.png)
Or you can just select the word and a notification pops up:


![Uhr](/images/uhr.png)


If you'd like to contribute to the extension, you can open the visual studio project wrapper directly.


Because of Google online app store is blocked inland, users of mainland should download **crx** file and install the extension manually.


The extension is being transported to **firefox** now, currently notification feature has successfully been transported.

