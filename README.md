# TabSwitcher 

TabSwitcher is an extension for Chrome that allows you to switch tabs using your
keyboard by typing only a few characters of the tab's title or URL.

It is inspired by TextMate and Vim's Command-T.

## What works 

- Triggering it with Control-\
- ESC to hide the UI
- Jumping to the best match with Enter
- Highlight matches 

## TODO

- Improve fuzzy matching algorithm:
  - Use some of Vim's Command-T improvements
  - Make case insensitive
  - Match on tab titles as well as URL (?)
  - Match over all windows, not just current window
- Activating TS in a tab should deactivate it from all other tabs
- Go to any match by clicking on it or navigating with arrows ( or ctrl-j / ctrl-k ? )
- Get a config page to select an hotkey 
- Make UI prettier
