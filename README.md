# FirefoxCustomisations
contains all the custom css themes and extensions i use for firefox

## Extensions
**NOTE: This only contains the extensions that change the styling in any way**
- Firefox Colour https://addons.mozilla.org/en-GB/firefox/addon/firefox-color/ (this is not needed as it was only used to generate the theme files)
- Tree Style Tab https://addons.mozilla.org/en-GB/firefox/addon/tree-style-tab/

## Custom css
- userChrome.css [./userChrome.css](./userChrome.css) see [./userChrome.md](./userChrome.md)

## Toolbar Customisations
NOTE this will look different without the Custom css above

![toolbar customisation image](./ToolbarCustomisation.png)

to get there go to (there are other ways to get there)

`≡` > `More tools` > `Cusomise toolbar...`

Aditionaly I have my bookmark bar set to always show

in the Cusomise toolbar page at the bottom go to

`Toolbars` > `Bookmarks Toolbar` > `Always Show`

another thing that I have changed is the Density again at the bottom of the Cusomise toolbar page.

(Firefox version 89 and up)
> However when aplying this setting a pref needs to be changed 
> go to `about:config` and set the `browser.compactmode.show` to `true`

then go to

`Density` > `Compact`
> this has a `not supported` warning in newer versions from my experience it works fine

## Theme
Generated with Firefox Colour.

To use can be ziped and renamed from `.zip` to `.xpi`. (note there is issues with this method as it has to be privately published)

Should also be available in the releases.

Alternativly if you have the Firefox Colour Extension installed you can find a share link [here](https://color.firefox.com/?theme=XQAAAAJmAQAAAAAAAABBKYhm849SCia73laEGccwS-xMDPsqvXkIbAF6EJDWcx9sS_Bi3JZGE6ZZI2STfI2PTljkk0BgVDr_x5nZIXQTNQvpV_y9uYuRVo-3iuAeC3IhKKigWxnnt8IC9aL4MJRjxEDRWMsuraA9rnFyohT3vrE9RZKNjKeaMRfWTVjoxTeTWfQ0CLgoJUAACix4S9wYQm_9woPubekmFhNQRXEkMoieDj1kPAQWMuXJNZaicOZajWZKGa8e88lwYrrY5u2SXFJ8x36ImRrOaZhMPDx19HQNPbxb-pCTVun__uE9Kw)

## Extension Data
**COMMING SOON**

## Broser Pref's
> ### How to acctualy use these options
> 
> go to `about:config` accept the warning
> 
> then in the search bar search for the pref you want to change
> 
> then change the value to the desired value

to start the ones i allready mentioned

`browser.compactmode.show` = `true`

`toolkit.legacyUserProfileCustomizations.stylesheets` = `true`

to change the ctrl+tab menu to do like most other apps (i.e. most recently used first)

`browser.ctrlTab.sortByRecentlyUsed` = `true`


