# VSConfig

## Contents

- [Toggle Comments with ⌘+/](#toggle-comments-with-)
- [Don't copy blank lines to clipboard](#dont-copy-blank-lines-to-clipboard)
- [Disable Debugging Just My Code](#disable-debugging-just-my-code)

## Toggle Comments with ⌘+/

**Visual Studio > Tools > Options > Environment > Keyboard**

- `Edit.CommentSelection`
  - Remove `Ctrl+/ (Text Editor)`
- `Edit.UncommentSelection`
  - Remove `Ctrl+/ (Global)`
  - Remove `Ctrl+Shift+/ (Text Editor)`
- `Edit.ToggleLineComment`
  - Remove `Ctrl+K+, Ctrl+/ (Text Editor)`
  - Assign `Ctrl+/ (Global`)

**Parallels > Preferences > Shortcuts**

- Add `⌘/` -> `Ctrl+/`

## Don't copy blank lines to clipboard

**Visual Studio > Tools > Options > Text Editor > All Languages > General**

- Uncheck: _"Apply Cut or Copy to blank lines when there is no selection"_

## Disable Debugging Just My Code

### Tools > Options (or Debug > Options) > Debugging > General

- Uncheck: _"Enable Just My Code"_
