# adapt-media-brightcove

This is an extension of [adapt-contrib-media](https://github.com/adaptlearning/adapt-contrib-media) adding Brightcove as a possible video source.
It uses an iframe pointing to Brightcove endpoint.
The default media-element controls are hidden in favour of brightcove client-customized player.

The component can be used as Media component. 
This is a work in progress project. Currently none of the media functionalities (such as events, cc, etc) are available when using Brightcove.

### Attributes

**_component** (string): This value must be: `media`.

**_classes** (string): CSS class name to be applied to **Media**’s containing div. The class must be predefined in one of the Less files. Separate multiple classes with a space.

**_layout** (string): This defines the horizontal position of the component in the block. Acceptable values are `full`, `left` or `right`.  

**instruction** (string): This optional text appears above the component. It is frequently used to
guide the learner’s interaction with the component.  
**_media** (object):

>**useBrightcove** (bool): If set to 'true', will play videos from Brightcove.

>**brightcove** (string): Brightcove video configurations.

>>**accountId** (string): This is the Brightcove account id.
>>**playerId** (string): This is the Brightcove player id.
>>**videoId** (string): This is the Brightcove video id.
