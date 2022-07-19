# userChrome.css

this is a customisation that alows almost full control over how firefox looks

## How to install

first go to [about:support](#) in firefox and under the `Profile Folder` Row press the button that says `[Open Folder]`.

This should open the firefox profile in your file browser.

If the folder dosen't contain a `chrome` folder create it.

The pref `toolkit.legacyUserProfileCustomizations.stylesheets` should be set to true in [about:config](#)

Put the userChrome.css in the folder and the css rules should get applied to Firefox after a restart.

## How the userChrome.css file is structured

the file is split into sections within each section there are multiple selectors.

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
