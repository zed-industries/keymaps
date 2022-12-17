# keymaps

This repository contains keymaps that emulate the feel of other editors.

- [Keymap reference](https://zed.dev/docs/configuration/key-bindings)
- [Where are my configuration files located?](https://zed.dev/faq#where-are-my-configuration-files-located?)

## Notes

- If a key combination doesn't work as expected and the issue isn't related to a mistake in the `keymap.json`, Zed likely doesn't currently support the action
    - Ex: Zed currently cannot override any key combinations that involve a mouse click (multi-cursor rectangular selection)
- All keybindings are mapped, even ones that are defaults for Zed.  This pins down the keybinding in case the defaults ever change within Zed
    - Cannot pin `"enter": "menu::Confirm"`: https://github.com/zed-industries/feedback/issues/789
