# userChrome.css

this is a customisation that alows almost full control over how firefox looks

## How to install

first go to [about:support](#) in firefox and under the `Profile Folder` Row press the button that says `[Open Folder]`.

This should open the firefox profile in your file browser.

If the folder dosen't contain a `chrome` folder create it.

The pref `toolkit.legacyUserProfileCustomizations.stylesheets` should be set to `true` in [about:config](#)

Add the contents of `userChrome.css` and `userContent.css` to the top of the existing files in the folder and add the `RJUserChrome` and `RJUserContent` folders either with `mklink` or just copying them.

The css rules should get applied to Firefox after a restart.

## How the userChrome.css file is structured

the contents of the `userChrome.css` and `userContent.css` files just link to the files in the two folders of the same names and each file in those folders are individual sections

each section works on its own without the need of the other sections.

each rule is documented well enough to understand what everything does and with some knowledge of css would be easy enough to change.

## What it does

at the moment it
- hides all the tabs except pinned and the current tab
- if the sidebar is the tree style tab
  + hides the sidebar title
  + hides the sidebar close button
  + moves the dropdown to the bottom
  + removes the border between the sidebar and the titlebar
  + makes the sidebar only show when hovering on it or on the leftmost pixel in f11 fullscreen mode
- stops the titlebar's laggy slideup animation on entering f11 fullscreen mode
- hides the translate text popup when text is selected
- has a f11 lite mode that works with (https://github.com/RJ-Infinity/UserChromeScriptLoader)
- fixes the missing top border
