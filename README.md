# Developer Buddy

Ability to transform any hands-drawn design into a HTML code with AI.  It is a voice based solution which speeds up the development effort for creating static screens by replacing the UI developer with AI Service. Works on Amazon echo and google home devices.

Extending the Microsoft Sketch2code to leverage Alexa capabilities. Thank to  Sketch2Code which transforms a handwritten user interface design from a picture to valid HTML markup code.


# Happy Path!
1) User want to transform any hands-drawn design into a HTML code would send a email 
2) User to Alexa :  " Have you got a email with subject 'Draw to Code' with attachments "
3) Alexa : " yes i got it one email with one attachment"
4) User : " OK, download the attachment and reply the with the webpage"
5) The Alexa app should convert the attachment which is hand drawn design of a web page
      a) Identify the form elements ( like buttons , textboxes, headings)
      b) Identify the hand written letters in the image
      c) Create a new Web page with above inputs 
      d) reply to email with the webpage as attachement  or the url of webpage deployed
      
      

### Tech

Dillinger uses a number of open source projects to work properly:

* Asp net
* Azure Cloud
* Alexa SDK
* Google SDK
* Jovo
* [node.js] - evented I/O for the backend
* [jQuery]  


Happy Path
===========
open developer buddy
check emails
convert image to code
