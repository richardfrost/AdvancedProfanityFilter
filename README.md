# Advanced Profanity Filter
[![Build Status](https://flat.badgen.net/travis/richardfrost/AdvancedProfanityFilter/master)](https://travis-ci.com/richardfrost/AdvancedProfanityFilter)
[![Chrome Web Store](https://flat.badgen.net/chrome-web-store/users/piajkpdbaniagacofgklljacgjhefjeh?color=blue)](https://chrome.google.com/webstore/detail/advanced-profanity-filter/piajkpdbaniagacofgklljacgjhefjeh)
[![Chrome Web Store](https://flat.badgen.net/chrome-web-store/stars/piajkpdbaniagacofgklljacgjhefjeh?color=blue)](https://chrome.google.com/webstore/detail/advanced-profanity-filter/piajkpdbaniagacofgklljacgjhefjeh)
[![Discord](https://flat.badgen.net/badge/icon/discord?icon=discord&label)](https://discord.gg/MpE5Z3f)
[![paypal](https://flat.badgen.net/badge/paypal/donate/FFC439)](https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=XFL36QJY752R6&source=url)
[![Patreon](https://flat.badgen.net/badge/icon/patreon/F96854?icon=patreon&label)](https://www.patreon.com/richardfrost)

A browser extension to filter profanity from webpages.

For an overview of features and options, please head to the [wiki](https://github.com/richardfrost/AdvancedProfanityFilter/wiki).

### Installation
| Browser | Download |
|---------|----------|
| Chrome  | [Chrome Web Store](https://chrome.google.com/webstore/detail/advanced-profanity-filter/piajkpdbaniagacofgklljacgjhefjeh) |
| Firefox | [Firefox Add-ons](https://addons.mozilla.org/firefox/addon/advanced_profanity_filter) |
| Edge    | [Microsoft Edge Addons](https://microsoftedge.microsoft.com/addons/detail/lhnbdlbhcokmgpjenkjolnhdnkphnkam) |
| Edge (Legacy) | [More Info](https://github.com/richardfrost/AdvancedProfanityFilter/issues/102) |
| Opera   | [Opera addons](https://addons.opera.com/en/extensions/details/advanced-profanity-filter/) |
| Android | [Kiwi](https://play.google.com/store/apps/details?id=com.kiwibrowser.browser) or [Firefox](https://github.com/richardfrost/AdvancedProfanityFilter/issues/243#issuecomment-726218625) |
| iOS/Other | [Bookmarklet Info](https://github.com/richardfrost/AdvancedProfanityFilter/wiki/Bookmarklet) |
| TV Cast | [Instructions](https://github.com/richardfrost/AdvancedProfanityFilter/wiki/Audio#watch-on-tv) - [Discussion](https://github.com/richardfrost/AdvancedProfanityFilter/issues/206) |

### Features
* Filter modes
    * Censor - Hide offending words
    * Substitute - Replace offensive words
    * Remove - Remove offensive words
* Customizable word and substitution lists
* Works everywhere, including popular pages such as:
    * Facebook
    * Pinterest
    * Reddit
    * Twitter
* [Audio muting](https://github.com/richardfrost/AdvancedProfanityFilter/wiki/Audio) for videos on supported sites:
    * Amazon Video
    * Hulu
    * Netflix
    * Plex
    * Vudu
    * YouTube
    * And more! You can even add your own! ([advanced](https://github.com/richardfrost/AdvancedProfanityFilter/wiki/Custom-Audio-Muting-Site))

For a detailed overview of the features and settings, please see the [Getting Started page](https://github.com/richardfrost/AdvancedProfanityFilter/wiki).

### Issues, Suggestions or Feedback?
* Found a bug? Please open an [issue](https://github.com/richardfrost/AdvancedProfanityFilter/issues/new).
* Have a great idea to improve the project? Want to share some feedback? Head over [here](https://goo.gl/forms/LTqFpJ0mCTsrgGgf2).

### Beta Testing
If you would like to help with development, but don't have experience coding, its very helpful to have users test a release candidate before actually publishing it to everyone. If you are interested in testing new versions see [this page](https://github.com/richardfrost/AdvancedProfanityFilter/wiki/Beta-Testing) for more information.

### Development
This project is written in TypeScript, and during the build/package process it will be converted to JS. Please see `package.json`'s scripts for more info on the process.

Getting started
```
npm install
```

To Build the extension
```
npm run package
```
