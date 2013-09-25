# ConfCast #
A more intuitive conferencing platform.

ConfCast is essentially an authorization wrapper for the existing [Google
Cast extension](https://chrome.google.com/webstore/detail/google-cast/boadgeojel
hgndaghljhdicfkmllpafd) - awaiting licensing to see if this project can legally
extend Google Cast or if a new Chrome extension will need to be written.

ConfCast is aimed at providing the following seamless experience:

* User creates a Google Calendar entry and invites some people and a Room 
Resource (see ["Schedule resources via Google Calendar"](https://support.google
.com/calendar/answer/44105?topic=8605) for instructions in creating Room 
Resources that can be schedule in Google Calendar)
* User shows up in correct room within timespan of meeting scheduled
* User either screenshares, or opens a hangout - all of this shows up on the 
screen for the conference room they're in.

## Components ##
* Chromecast & display
* ConfCast Client
* ConfCast Server

## Chromecast ##
Buy one [here](http://www.google.com/intl/en/chrome/devices/chromecast)

## ConfCast Client ##
This is the application the client uses to cast, it will come initially 
in one flavor with more to come.

* Chrome extension

Planned for future release:

* Android application

## ConfCast Server ##
This is the application which authorizes individuals to cast to a conference 
room within a given time window. This application will be available in 
two flavors:

* Debian package for installation on your own server(s)
* Appengine

+foobar example
