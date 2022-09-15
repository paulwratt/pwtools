# pwtools
 pool together various pwtools including CLI (`*.sh`), userscripts (`*.user.js`), stylesheets (`*.stylish.css`), etc

(as of September 2022 - [https://paulwratt.github.io/pwtools/](https://paulwratt.github.io/pwtools/))
  
## the list
(my full GitHub repo names are used, just to make it easier to find individual repos, or for when cloning)

 - [imperial-hero-2-pwtools](https://github.com/paulwratt/imperial-hero-2-pwtools) - Imperial Hero II (web browser game)
   - [75% Zoom](https://github.com/paulwratt/imperial-hero-2-pwtools/blob/master/zoom75.ih2.user.js) - when using zoom 75% fixes item slots, panel layouts, dropdowns, etc - ([install&nbsp;.user.js&nbsp;v3.02](https://github.com/paulwratt/imperial-hero-2-pwtools/raw/master/zoom75.ih2.user.js))
   - [Export Crafting Report](https://github.com/paulwratt/imperial-hero-2-pwtools/blob/master/export.ih2.user.js) - allow export Crafting Report as selectable text (not the CRX) - ([install&nbsp;.user.js&nbsp;v1.06](https://github.com/paulwratt/imperial-hero-2-pwtools/raw/master/export.ih2.user.js))
 - [torn-city-pwtools](https://github.com/paulwratt/torn-city-pwtools) - [Torn City](https://www.torn.com/) (web browser game)
   - [(old) DarkTheme Stylish CSS](https://github.com/paulwratt/torn-city-pwtools/blob/master/darktheme.torn.stylish.css) - the standalone CSS file version of the userscript stylesheet over-ride - ([preview](https://userstyles.org/styles/161398/darktheme-for-torn)&nbsp;[.stylish.css&nbsp;v3.08](https://github.com/paulwratt/torn-city-pwtools/raw/master/darktheme.torn.stylish.css))
   - [(old) DarkTheme userscript](https://github.com/paulwratt/torn-city-pwtools/blob/master/darktheme.torn.user.js) - this four year old CSS appears to be basis for the new Dark Mode - ([install&nbsp;.user.js&nbsp;v3.08](https://github.com/paulwratt/torn-city-pwtools/raw/master/darktheme.torn.user.js))
   - [FightClub userscript](https://github.com/paulwratt/torn-city-pwtools/blob/master/fightclub.torn.user.js) - Adds a fight button to every profile in Friends/Black lists, RApest compatible - ([install&nbsp;.user.js&nbsp;v1.10](https://github.com/paulwratt/torn-city-pwtools/raw/master/fightclub.torn.user.js))
   - [ReAttack Pest userscript](https://github.com/paulwratt/torn-city-pwtools/blob/master/rapest.torn.user.js) - Allow to add player to Friends or Black lists after being mugged. Allow ReChain for "+3.00 fair fight" profiles in Friends or Black lists (see wiki for usage) - ([install&nbsp;.user.js&nbsp;v2.11](https://github.com/paulwratt/torn-city-pwtools/raw/master/rapest.torn.user.js))
 - [nz-kiwibank-pwtools](https://github.com/paulwratt/nz-kiwibank-pwtools) - KiwiBank (NZ)
   - [Auto-Refresh Accounts](https://github.com/paulwratt/nz-kiwibank-pwtools/blob/main/kiwibank.user.js) after login, while you are waiting for your account transactions to update, randomly auto-click _Resfresh_ per minute (adjustable) - ([install&nbsp;.user.js&nbsp;v1.0.3](https://github.com/paulwratt/nz-kiwibank-pwtools/raw/main/kiwibank.user.js))
 - [gmail-html-pwtools](https://github.com/paulwratt/gmail-html-pwtools) - for Gmail Plain View (HTML, fast), not for Standard View (JS App, Slow)
   - [Multi-Select Checkboxes](https://github.com/paulwratt/gmail-html-pwtools/blob/main/gmail-html.user.js) adds (my) Gmail Standard View background, the missing _"Select All"_ checkboxes, and _full label names_ to the options dropdown menu - ([install&nbsp;.user.js&nbsp;v1.10.7](https://github.com/paulwratt/gmail-html-pwtools/raw/main/gmail-html.user.js))

## todo list

 - cli-debian-pwtools - a collection of various everyday command line _Comforts of Life_ (Debian/apt) shell scripts
 - github-pwtools - a collection of various GitHub & GH Gist specific scripts
 - gitlab-pwtools - the GitLab versions of the GH specific scripts
 - serenityos-devel-pwtools - a collection of GitHub related developer analysis CLI tools (classified commit details as text objects in the FileSystem - ie. grep-able)
 - bas-2.5-plus-pwtools - a collection of various [Bas](http://www.moria.de/~michael/bas/), [Bas-2.5-plus](https://github.com/paulwratt/bas-2.5-plus) & [Bas-2.5-pw](https://github.com/paulwratt/bas-2.5-pw), ECMA-116/ANSI-86/SBASIC (Dartmouth) Basic shell scripts and associated Basic program utilities

## how to use
 - **userstyles** use Stylish for FF/Chrome/Chromium/Android, or add Custom User CSS to you browser
 - **userscripts** require a GreaseMonkey compatible engine, like TamperMonkey, ViolentMonkey, etc
 - **cli scripts** require a `sh` compliant shell (most are), like Bash, Dash, Zsh, Csh, Ksh, Msh, Tsh, P9sh

### homepages
(hold CTRL while clicking to open links in a new window)

<img src="./docs/images/stylish.jpg" height=20> Stylish - 
<img src="./docs/images/greasemonkey.png" height=20> GreaseMonkey - 
<img src="./docs/images/tampermonkey.png" height=20> TamperMonkey - 
<img src="./docs/images/violentmonkey.png" height=20> Violentmonkey 

[ [Stylish](https://userstyles.org/) | [GreaseMonkey](https://addons.mozilla.org/en-US/firefox/addon/greasemonkey/) | [TamperMonkey](https://www.tampermonkey.net/) | [ViolentMonkey](https://violentmonkey.github.io/) ]

### installing

<img src="./docs/images/chrome.png" height=20> Chrome - 
<img src="./docs/images/firefox.png" height=20> Firefox - 
<img src="./docs/images/edge.png" height=20> Edge - 
<img src="./docs/images/opera.png" height=20> Opera - 
<img src="./docs/images/vivaldi.png" height=20> Vivaldi - 
<img src="./docs/images/maxthon.png" height=20> Maxthon - 
<img src="./docs/images/chromium.png" height=20> Chromium based

 - Chrome Extension : [ [Stylish](https://chrome.google.com/webstore/detail/stylish-custom-themes-for/fjnbnpbmkenffdnngjfgmeleoegfcffe) 
| [TamperMonkey Stable](https://chrome.google.com/webstore/detail/tampermonkey/dhdgffkkebhmkfjojejmpbldmpobfkfo) 
| [TamperMonkey Beta](https://chrome.google.com/webstore/detail/tampermonkey-beta/gcalenpjmijncebpfijmoaglllgpjagf) 
| [Violentmonkey](https://chrome.google.com/webstore/detail/violentmonkey/jinjaccalgkegednnccohejagnlnfdag) ]
 - FireFox Extensions : [ [GreaseMonkey](https://addons.mozilla.org/en-US/firefox/addon/greasemonkey/) | [TamperMonkey](https://addons.mozilla.org/en-US/firefox/addon/tampermonkey/) | [TamperMonkey Beta](https://www.tampermonkey.net/?browser=firefox) | [Violentmonkey](https://addons.mozilla.org/firefox/addon/violentmonkey/) ]
 - Microsoft Edge Addons : [ [TamperMonkey](https://microsoftedge.microsoft.com/addons/detail/iikmkjmpaadaobahmlepeloendndfphd) | [TamperMonkey Beta](https://microsoftedge.microsoft.com/addons/detail/fcmfnpggmnlmfebfghbfnillijihnkoh) | [Violentmonkey](https://microsoftedge.microsoft.com/addons/detail/eeagobfjdenkkddmbclomhiblgggliao) ]
 - Opera Addons : [ [TamperMonkey](https://addons.opera.com/en/extensions/details/tampermonkey-beta/) ]
 - Safari Browser : [ [(v6-v11) TamperMonkey](https://www.tampermonkey.net/?browser=safari) | [(v12+|MacOS 10.13+) TamperMonkey](https://apps.apple.com/app/apple-store/id1482490089?pt=117945903&ct=tm.net&mt=8) ]
 - Maxthon Extentions : [ [(v4|v5) Violentmonkey](http://extension.maxthon.com/detail/index.php?view_id=1680) ]
 - Android : [ [(UC Browser) TamperMonkey](https://play.google.com/store/apps/details?id=net.tampermonkey.uc) | [Dolphin) TamperMonkey](https://play.google.com/store/apps/details?id=net.tampermonkey.dolphin) ]

### find more
 - userstyles : [ [site styles](https://userstyles.org/categories/site) | [global styles](https://userstyles.org/categories/global) | [android styles](https://userstyles.org/categories/android) ]
 - userscripts : [ [TamperMonkey](https://www.tampermonkey.net/scripts.php) 
 | [UserScript.Zone](https://www.userscript.zone/) 
 | [GreasyFork](https://greasyfork.org/) 
 | [OpenUserJS](https://openuserjs.org/) 
 | [GitHub Gist](https://gist.github.com/search?l=JavaScript&o=desc&q=%22%3D%3DUserScript%3D%3D%22&s=updated) ]
 - shellscripts : [ []() | []() ]
