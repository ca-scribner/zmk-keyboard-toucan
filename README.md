# ZMK config for beekeeb Toucan Keyboard

[The beekeeb Toucan Keyboard](https://beekeeb.com/toucan-keyboard/) is a wireless split 42-key column‑stagger keyboard that a display and a trackpad, with an aggressive stagger on the pinky columns.

# Usage notes

## Editing the keymap

### Building a keymap file

Use [Nick Coutsos's Keymap Editor](https://nickcoutsos.github.io/keymap-editor/) to edit keymap files.

## Updating the keymap without flashing the keyboard

Use the [ZMK Studio](https://zmk.studio/) to connect to the keyboard to update the keymap without flashing.

## Generating Keymap drawings

```
uvx --from keymap-drawer keymap parse -c 10 -z ./config/toucan.keymap > toucan_keymap.ya
uvx --from keymap-drawer keymap draw -z corne toucan_keymap.yaml > keymap.svg
```

# License

The code in this repo is available under the MIT license.

The included shield nice_view_gem is modified from https://github.com/M165437/nice-view-gem licensed under the MIT License.

ZMK code snippets are taken from the ZMK documentation under the MIT license.

The embedded font QuinqueFive is designed by GGBotNet, licensed under under the SIL Open Font License, Version 1.1.
