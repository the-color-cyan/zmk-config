# cyan's Corne ZMK Firmware

## External Resources

- [urob's zmk-helpers](https://github.com/urob/zmk-helpers) for some helpful macros.
- [M165437's nice-view-gem](https://github.com/M165437/nice-view-gem) for some sick nice!view visuals.
- [nickcoutsos' keymap-editor](https://github.com/nickcoutsos/keymap-editor) for basic inital layer editing and planning in an easier to visualize format.
- [caksoylar's keymap-drawer](https://github.com/caksoylar/keymap-drawer) for automated keymap image visualization so I know what buttons do what.

## Features

- [Timeless home row mods](https://github.com/urob/zmk-config?tab=readme-ov-file#timeless-homerow-mods)
- Hold-Taps on NAV layer
  - Taps register as `arrow keys`
    - Holds register as `home`, `end`, and `beginning/end of document`
  - Taps register as `backspace` and `del`
    - Holds register as `delete word backward/forward`
- Mod-Tap on layer keys
  - NAV/space
  - NUMSYM/return
  - {FN/SYS}/Esc
- Magic-Shift
  - Sticky-Shift on tap for next letter
  - Shift on hold
  - Caps-Word on double-tap
- Swappable base-layers
  - Colemak-DH
  - QWERTY
  - Gaming (QWERTY with each key set to only basic keypresses)

## Keymap (generated via [keymap-drawer](https://github.com/caksoylar/keymap-drawer))

![corne keymap](keymap-drawer/corne.svg)
   
## planned
- ~~Combos~~ implemented
- ~~QWERTY and gaming layers~~ implemented
- Mouse movement
- OS-navigation (GUI + ..., Alt + Tab, etc.)
