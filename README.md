Titanium-Mobile-Android-Touch-Sound
===================================

A simple way to toggle the touch sound on Titanium Views (View, Label, Image, etc)

Frustrated by the fact that every view in a Titanium Mobile Android project makes a touch sound, whether or not the view has a touch event applied to it?

Before you put your shoe through your computer, tell your client "That's just the way it is." or decide to change careers, give this module a spin.


How To:

var label = Ti.UI.createLabel({options....});

var touchSound = require('com.gstreetmedia.androidtouchsound');

touchSound.disable(label);

Enough said.

