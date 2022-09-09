# pwtools
 (as of September 2022)
  
 pool together various pwtools including CLI (`*.sh`), userscripts (`*.user.js`), stylesheets (`*.stylish.css`), etc

## how to use
 - **userstyles** use Stylish for FF/Chrome/Chromium/Android, or add Custom User CSS to you browser
 - **userscripts** require a GreaseMonkey compatible engine, like TamperMonkey, ViolentMonkey, etc
 - **cli scripts** require a `sh` compliant shell (most are), like Bash, Dash, Zsh, Csh, Ksh, Msh, Tsh, P9sh

### homepages
(hold CTRL while clicking to open links in a new window)

<center>
<img src="./docs/images/greasemonkey.png" height=20> GreaseMonkey 
<img src="./docs/images/tampermonkey.png" height=20> TamperMonkey
<img src="./docs/images/violentmonkey.png" height=20> Violentmonkey

[ [Stylish](https://userstyles.org/) | [GreaseMonkey](https://addons.mozilla.org/en-US/firefox/addon/greasemonkey/) | [TamperMonkey](https://www.tampermonkey.net/) | [ViolentMonkey](https://violentmonkey.github.io/) ]

<img src="./docs/images/chrome.png" height=20> Chrome 
<img src="./docs/images/firefox.png" height=20> Firefox 
<img src="./docs/images/edge.png" height=20> Edge 
<img src="./docs/images/opera.png" height=20> Opera 
<img src="./docs/images/vivaldi.png" height=20> Vivaldi
<img src="./docs/images/chromium.png" height=20> More Chromium based browsers
</center>

### installing
 - Chromium Extension : [ [Stylish](https://chrome.google.com/webstore/detail/stylish-custom-themes-for/fjnbnpbmkenffdnngjfgmeleoegfcffe) 
| [TamperMonkey Stable](https://chrome.google.com/webstore/detail/tampermonkey/dhdgffkkebhmkfjojejmpbldmpobfkfo) 
| [TamperMonkey Beta](https://chrome.google.com/webstore/detail/tampermonkey-beta/gcalenpjmijncebpfijmoaglllgpjagf) 
| [Violentmonkey](https://chrome.google.com/webstore/detail/violentmonkey/jinjaccalgkegednnccohejagnlnfdag) ]
 - FireFox Extensions : [ [GreaseMonkey](https://addons.mozilla.org/en-US/firefox/addon/greasemonkey/) |  ]

### find more
 - userstyles : [ [site styles](https://userstyles.org/categories/site) | [global styles](https://userstyles.org/categories/global) | [android styles](https://userstyles.org/categories/android) ]
 - userscripts : [ [TamperMonkey](https://www.tampermonkey.net/scripts.php) 
 | [UserScript.Zone](https://www.userscript.zone/) 
 | [GreasyFork](https://greasyfork.org/) 
 | [OpenUserJS](https://openuserjs.org/) 
 | [GitHub Gist](https://gist.github.com/search?l=JavaScript&o=desc&q=%22%3D%3DUserScript%3D%3D%22&s=updated) ]

## the list
(my full GitHub repo names are used, just to make it easier to find individual repos, or for when cloning)

 - [imperial-hero-2-pwtools](https://github.com/paulwratt/imperial-hero-2-pwtools) - Imperial Hero II (web browser game).
 - [torn-city-pwtools](https://github.com/paulwratt/torn-city-pwtools) - [Torn City](https://www.torn.com/) (web browser game).
   - [(old) DarkTheme Stylish CSS](https://github.com/paulwratt/torn-city-pwtools/blob/master/darktheme.torn.stylish.css) - the standalone CSS file version of the userscript stylesheet over-ride ([preview](https://userstyles.org/styles/161398/darktheme-for-torn) [.stylish.css v3.08](https://github.com/paulwratt/torn-city-pwtools/raw/master/darktheme.torn.stylish.css)).
   - [(old) DarkTheme userscript](https://github.com/paulwratt/torn-city-pwtools/blob/master/darktheme.torn.user.js) - this four year old CSS appears to be basis for the new Dark Mode ([install .user.js v3.08](https://github.com/paulwratt/torn-city-pwtools/raw/master/darktheme.torn.user.js)).
 - [nz-kiwibank-pwtools](https://github.com/paulwratt/nz-kiwibank-pwtools) - KiwiBank (NZ)
   - [Auto-Refresh Accounts](https://github.com/paulwratt/nz-kiwibank-pwtools/blob/main/kiwibank.user.js) after login, while you are waiting for you account transactions to update, randomly auto-click _Resfresh_ per minute (adjustable) - ([install .user.js v1.0.3](https://github.com/paulwratt/nz-kiwibank-pwtools/raw/main/kiwibank.user.js)).
 - [gmail-html-pwtools](https://github.com/paulwratt/gmail-html-pwtools/blob/main/gmail-html.user.js) - Gmail plain view (HTML, fast), not for Standard view (JS App, Slow).
   - [Multi-Select Checkboxes](https://github.com/paulwratt/gmail-html-pwtools/blob/main/gmail-html.user.js) adds (my) Gmail Standard View background, the missing _"Select All"_ checkboxes, and _full label names_ to the options dropdown menu - [install .user.js v1.10.3](https://github.com/paulwratt/gmail-html-pwtools/raw/main/gmail-html.user.js)

## todo list

 - cli-debian-pwtools - a collection of various everyday command line _Comforts of Life_ shell scripts
 - github-pwtools - a collection of various GitHub specific scripts
 - bas2.5plus-pwtools - a collection of various Bas & Bas-2.5plus ECMA/ANSI Basic scripts

