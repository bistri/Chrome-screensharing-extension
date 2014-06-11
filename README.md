Chrome-screensharing-extension
==============================

Chrome extension to use screen sharing feature with WebRTC

**Clone this extension and open the `manifest.json`:**

* line 2: modify the name attribute
* line 15-20: set all domains allowed use this extension

=

You can test this extension on the Bistri demo conference:

* http://bistri.com/demo/conf

=

## Note

You can use this extension within any WebRTC applications, it is vendor independant except for modification about allowed domains in `manifest.json`

## How to publish your extension

* Modify `manifest.json`
* Follow Google instructions to package the extension : https://developer.chrome.com/extensions/packaging
