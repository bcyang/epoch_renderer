# Chrome Extension - Epoch Renderer 

## Why

In our APIs, I intentionally use epoch timestamp in seconds (long / float) everywhere. The reasons are

- no confusion/ambiguity about the timezone
- no questions/preferences about rendering format

However, it introduces an obvious problem - it's not human readable.


## Solution

Make the broser smarter



## Installation

Until I release this into the Google/Chrome store...


### Manual Installation

1. clone this repo
2. go to chrome://extensions/
3. top-right corner, enable the `Developer mode`
4. click `Load unpacked` button and choose the directory
5. In the extension detail, check the `Pin to toolbar` so you can enable/disable it without uninstall/reinstall.

This comes with the benefit of changing the rendering yourself. Then simply `reload` the extension.

