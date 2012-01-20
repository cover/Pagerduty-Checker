Pagerduty Checker
=========

A very simple ruby script to check when something bad happens on Pagerduty and get notified immediately.

It uses the standard Ubuntu (and derivatives) notification system through notify-send, so make sure to have it installed. Feel free to fork this and add support for other notification systems.

Sound is from http://www.freesound.org/people/Nasse/sounds/91290/

PagerDuty logo is owned by PagerDuty Inc.

Requirements
------------

notify-send, amixer, mplayer

Installation
------------

- Clone this repo
- Make sure to have json installed with bundle install (not required for ruby 1.9)
- Set your data (email, password, subdomain) in the config.rb file
- Start the script or set it in the Autostart with (on KDE):

    ln -s /path/of/the/repo/pagerduty-checker ~/.kde/Autostart/
