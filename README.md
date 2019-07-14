# LIRI-Bot

What is Liri:

Liri is node-based programming that emualtes an AI assistant, like siri, cortana, alexa or whatever impersonal thing google has.

How Does it work:


Performance Demostration

https://cl.ly/3d568aa9947e/Screen%20Recording%202019-07-13%20at%2007.40.02.20%20PM.mp4


liri takes four general comands: concert-this, spotify-this, movie-this, and a default function named "do-what-it-says" which takes text from the file random.txt and inputs its default comand of spotify-this-song "I Want it That Way".

The "spotify-this" works by taking the song provided in the argument by the user and returning song information.
Similarly, this is done by the other two commands "movie-this" and "concert-this" They all point at various API that correspond their particular call. "spotify-this-song" would use the same keys for "do-what-it-says" since the comand defaults to the spotify command.

Instructions:
There are 4 commands

node liri.js spotify-this-song "[song name in here]"
to get information of a song title

node liri.js movie-this "[movie name here]"
to get information on a movie

node liri.js concert-this "[ put artist name here]"
to get concert info

node liri.js do-what-it-says
to get default action of a retrival to spotify on the songs titled "I Want it That Way"


Project purpose to teach and demonstrate the use of javaScript for back-end server use.


Dependencies
A command line terminal is the only necessary application needed to run this app.

Installing
Once downloaded, run the command "npm install" to download the necessary items for your package.json

Executing program
The program is run through your command line terminal with the following: *node liri.js (command) "(argument)"

Link to version:

Role: Documentation 

