# jitsi-plugins
A collection of jitsi plugins to customize your private Jitsi instance

## Jitsi-meet plugins
 
 Here is a list of plugins that can be added to your jisti meet we interface;
 
 - [Jitsi party button](https://gum.co/LnVyo) :
 > This plugin allows you to add a 'party poppers' to your jitsi interface.
 People can use it as a quick way to share their hapiness.
 
 - [Jitsi Timer](https://gum.co/CBOoh) :
 > This plugin allows the conference moderator to start a timer that will be visible to all participant.
 This is a good way to timebox discussions
 
 ### Install
 
The Jitsi Meet react client has currently no build in mecanisme to allow plugin,
but it is still possible to have some plugins with at least 2 differents approaches.

The first approache is basically adding a new JS file to be loaded by the front-end when it load.
There are two ways to do so : 
 - modifing the default index.html page to include some new tags.
 - adding the script url in the `analytics.scriptURLs` array fo the `config.js`
 
 The second approach would be applying a patch on tope of the jitsi meet client code and build it.
 This technique is more invasive but allows for more important customisation.
 Each plugins should come with his manual instruction to be installed.
 
 ## Prosody plugins
 
 TDB
