# adapt-media-brightcove

This is an extension of [adapt-contrib-media](https://github.com/adaptlearning/adapt-contrib-media) adding Brightcove as a possible video source.
It uses an iframe pointing to Brightcove endpoint.
The default media-element controls are hidden in favour of brightcove client-customized player.

The component can be used as Media component. 
This is a work in progress project. Currently none of the media functionalities (such as events, cc, etc) are available when using Brightcove.

### Attributes

**_component** (string): This value must be: `media-brightcove`.

**_media** (object):

>**useBrightcove** (bool): If set to 'true', will play videos from Brightcove.

>**brightcove** (string): Brightcove video configurations.

>>**accountId** (string): This is the Brightcove account id.
>>**playerId** (string): This is the Brightcove player id.
>>**videoId** (string): This is the Brightcove video id.
