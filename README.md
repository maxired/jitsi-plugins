# jitsi-plugins
A list of jitsi plugins to install on private server

## Jitsi-meet plugins

The Jitsi Meet react client has currently no build in mecanisme to allow plugin,
but it is still possible to have some plugins with at least 2 differents approaches.

The first approache is basically addind a new JS file to be loaded by the front-end when it load.
There are two ways to do so : 
 - modifing the default index.html page to include some new tags.
 - adding the script url in the `analytics.scriptURLs` array fo the `config.js`
 
 Here is a list of plugins that can be added to your jisti meet we interface;
 
 ### Jitsi party button
 
 This plugin allows you to add a 'party poppers' to your jitsi interface.
 People can use it as a quick way to share their hapiness.
 Available on https://gum.co/LnVyo
 
 ### Jitsi Timer
 
 This plugin allows the conference moderator to start a timer that will be visible to all participant.
 This is a good way to timebox discussions
 
 Available on https://gum.co/CBOoh
 
 ## Prosody plugins
 
 TDB
