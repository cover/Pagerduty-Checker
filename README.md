Pagerduty Checker
=========

A very simple ruby script to check when something bad happens on Pagerduty and get notified immediately.

KDE notification only for now (using kdialog), feel free to fork this and add support for other notification systems.

Sound is from http://www.freesound.org/people/Nasse/sounds/91290/

Requirements
------------

KDE/kdialog, amixer, mplayer

Installation
------------

- Clone this repo
- Make sure to have json installed with bundle install (not required for ruby 1.9)
- Set your data (email, password, subdomain) in the config.rb file
- Start the script or set it in the Autostart with (on KDE):

    ln -s /path/of/the/repo/pagerduty-checker ~/.kde/Autostart/
