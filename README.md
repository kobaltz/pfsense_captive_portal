# pfSense Captive Portal

Get rid of the boring default pfSense display and swap it out for a pretty and responsive page.

## Themes

Vanilla - [Source](https://github.com/kobaltz/pfsense_captive_portal/tree/gh-pages/vanilla) - [Example](https://kobaltz.github.io/pfsense_captive_portal/vanilla/login-username-password.html)

Azmind - [Source](https://github.com/kobaltz/pfsense_captive_portal/tree/gh-pages/azmind) - [Example](https://kobaltz.github.io/pfsense_captive_portal/azmind/login-username-password.html)

## Installing

Log into your pfSense dashboard and go to Services > Captive Portal.

Edit your Captive Portal and upload each of the HTML files in this repository to the appropriate places.

  - Portal Page Contents -> login.html
  - Auth error page contents -> error.html
  - Logout page contents -> logout.html

![Settings](settings.png)

## Contributing a Theme

Given the nature of how simple these are (not many files involved), pull requests which add new themes are greatly appreciated! If you decide to contribute a theme, please copy one of the existing folders and replace the existing content with your theme. Try to keep everything embedded as I want to keep these as simple as possible to install. I personally feel that the available themes here should not require users to upload separate dependent files. Also, if you are using a framework, try to remove the unused CSS to minimize the size of the files. You can do this by using something like `uncss`. You can run `npm install -g uncss` and then run `uncss FILENAME.HTML > output.css` to generate the list of used css styles. Also, if you have copied someone else's form and styles, please give the appropriate mentions.



