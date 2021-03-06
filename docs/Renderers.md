Renderers
=========

Renderers allow you to automatically pull up additional information on Alerts. To use a Renderer, you have to first register it on an Alert field. Once you've done that, the Renderer will execute whenever you view that Alert.


Usage
-----

To configure Renderers, you first need to be viewing an Alert. Find the field that you want to add a renderer to and click the pencil icon on the far right to pull up the config. Select a Renderer from the dropdown and hit apply.

![Renderer config](/docs/imgs/renderer_config.png?raw=true)

You can save this configuration by clicking on the dropdown next to 'Add Note' and selecting from the list. Click 'Save Renderers', which will apply this configuration to all Alerts generated by the Search.

![Renderer config save](/docs/imgs/renderer_save.png?raw=true)


Types
-----

### IP ###

![IP renderer](/docs/imgs/renderer_ip.png?raw=true)

Display GeoIP information on a IP address.


### MAC ###

![MAC renderer](/docs/imgs/renderer_mac.png?raw=true)

Display vendor information on a MAC address.


### Link ###

![Link renderer](/docs/imgs/renderer_link.png?raw=true)

Turn all URLs into clickable links.


### Stacktrace ###

Render pre-formatted content (like stack traces)
