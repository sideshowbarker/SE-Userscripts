# SE-Userscripts
A collection of user scripts for the Stack Exchange network.

### SOCVR-Alert | [Install](https://github.com/Jacob-Gray/SE-Userscripts/raw/master/current/SOCVR-Alert.update.user.js)

SOCVR-Alert is a script to used in the [SO Close Vote Reviewers](http://chat.stackoverflow.com/rooms/41570/so-close-vote-reviewers) chatroom on Stack Overflow. It parses incoming messages and alerts you of <kbd>cv-pls</kbd> requests and [Smoke Detector](https://github.com/Charcoal-SE/SmokeDetector) posts.

Usage:

1. Join the [SOCVR chatroom](http://chat.stackoverflow.com/rooms/41570/so-close-vote-reviewers)(Or a room that has smoke-detector/cv-pls requests)
2. Leave the room open in your browser to be notified.

Features:
- Notifies of new SD and <kbd>cv-pls</kbd> posts
- Alerts you in a desktop notification:

  <img src="http://i.imgur.com/eRgEuzQ.png?1" width=250>
  <img src="http://i.imgur.com/GYtbrqb.png?1" width=250>

- Clicking on the notification will take you directly to the question/answer
- Checks for updates, and alerts you when they are ready to install

```
// @match        *://chat.meta.stackexchange.com/rooms/*
// @match        *://chat.stackoverflow.com/rooms/*
// @match        *://chat.stackexchange.com/rooms/*
// @require      https://code.jquery.com/jquery-2.1.4.min.js
```
[Report an issue](https://github.com/Jacob-Gray/SE-Userscripts/labels/socvr-alert)
