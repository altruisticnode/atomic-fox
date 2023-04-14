<p align="center">
    <img src="./preview/wide.png"></img>
</p>
<h3 align="center">Atomic Fox</h3>

<div align="center">

  [![Tweet](https://img.shields.io/twitter/url/https/shields.io.svg?style=social)](https://twitter.com/intent/tweet?text=%F0%9F%93%A2%20Atomic%20Fox%20is%20a%20configuration%20set%20that%20cleans%20up%20and%20minimizes%20your%20Firefox%20UI%20for%20the%20most%20clutter-less%20experience.%20Feel%20free%20to%20try%20it%20out%20here%20and%20enjoy%21&url=https://github.com/altruisticnode/atomic-fox)
  [![Status](https://img.shields.io/badge/status-active-success.svg)](https://github.com/altruisticnode/atomic-fox)
  [![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

</div>

## Table of Contents
- [About the Project](#about-the-project)
  * [Description](#description)
- [Getting Started](#getting-started)
  * [Firefox CSS](#firefox-css)
  * [Night Tab Configuration](#night-tab-configuration)
- [Preview](#preview)
- [License](#license)
- [Acknowledgements](#acknowledgements)

## About <a name = "about-the-project"></a>
### Description <a name = "description"></a>
This project includes an extremely minimalistic and light `chrome` modification of the [Firefox](https://en.wikipedia.org/wiki/Firefox) browser client.

As an addition, this also includes an optional configuration set for the [Night Tab](https://addons.mozilla.org/en-US/firefox/addon/nighttab/) start-up page extension.

As the name *atomic* implies, this is a very minimal configuration. You can view all of the stylesheet overrides in the [chrome](/chrome/) directory.

## Getting Started <a name = "getting-started"></a>
### Firefox CSS <a name = "firefox-css"></a>
1. Head over to `about:config` in Firefox
    - Set `toolkit.legacyUserProfileCustomizations.stylesheets` to true
    - Set `browser.compactmode.show` to true
2. Head over to `about:support` and find your `Profile Directory`
3. Copy the entire [chrome](/chrome/) folder into the `Profile Directory`
4. Enable compact mode (density) through the [Toolbar Settings](https://support.mozilla.org/en-US/kb/customize-firefox-controls-buttons-and-toolbars)
5. Restart Firefox and you're good to go 😉

### Night Tab Configuration <a name = "night-tab-configuration"></a>
1. Install the extension through Firefox: [Night Tab](https://addons.mozilla.org/en-US/firefox/addon/nighttab/)
2. Click into the settings (gear icon) on the top right
3. Navigate to the `Data` tab on the sidebar
4. Import the `config.json` from the [night-tab directory](/night-tab/)

## Preview <a name = "preview"></a>
All previews can be found in the [preview](/preview/) directory. It includes a wide preview, a block preview, and a preview with depth perspective.

<h4 align="center">Block Style Preview (From Window Manager)</h4>
<p align="center">
    <img src="./preview/block.png"></img>
</p>

## License <a name = "license"></a>
Distributed under the [MIT](https://choosealicense.com/licenses/mit/) License. 

Please see the [LICENSE](/LICENSE) for more information.

## Acknowledgements <a name = "acknowledgements"></a>
This section includes a useful list of sources that have helped my project— Either directly, or through other means such as inspiration.
- [Mozilla's Firefox](https://www.mozilla.org/firefox/)
- [Night Tab Extension](https://addons.mozilla.org/en-US/firefox/addon/nighttab/)
- [Amadeus's NT Configuration](https://github.com/AmadeusWM)