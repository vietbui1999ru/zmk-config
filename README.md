# My `eyelash_corne` keymap - [Aliexpress](https://www.aliexpress.us/item/3256808273876596.html?spm=a2g0o.order_list.order_list_main.15.7a271802RMqUdF&gatewayAdapt=glo2usa)

---

# Objectives: 
+ To migrate to colemak dh but also maintain muscle memory on my current workflow, optimized for:
    - [x] Neovim
    - [x] Tmux
    - [x] Aerospace
    - [x] Touch typing
    - [x] MacOS & Linux (suck it Microslop)
+ To increase efficiency in my typing and reduce key-travel time.
+ To cook up more AI slop with the new colemak dh typing @140 WPM.


## Specs & Features

| Spec | Detail |
|------|--------|
| Keyboard | Eyelash Corne (AliExpress) |
| Controller | nice!nano (nRF52840) |
| Firmware | ZMK v0.3.0 |
| Keys | 42 (3×6 + 3 thumbs per side) |
| Connectivity | Bluetooth 5.0 / USB-C |
 
 
## Layer Overview
 
| # | Name | Access | Purpose |
|---|------|--------|---------|
| 0 | QWERTY | Default | Base typing layer |
| 1 | COLEMAK | FN layer macro | Colemak-DH alpha swap |
| 2 | NUM | Left mid thumb | Numbers + AeroSpace workspaces |
| 3 | SYM | Right mid thumb | All symbols and brackets |
| 4 | NAV | Both mid thumbs together | Vim-style navigation + AeroSpace window mgmt |
| 5 | MEDIA | `Z+/` combo toggle | RGB, volume, mouse |
| 6 | FN | `Q+P` combo toggle | Function keys, Bluetooth, system |


## Thumb Cluster
 
```
Left:  [ CMD ]  [ NUM ]  [ SPACE ]
Right: [ RET ]  [ SYM ]  [ HYPER ]
```

| Key | Action | Notes |
|-----|--------|-------|
| Left outer | `CMD` (LGUI) | Pure key — no hold-tap |
| Left mid | `NUM` layer | Pure `&mo` — opens numbers workspace |
| Left inner | `SPACE` | Pure key — no hold-tap |
| Right inner | `RETURN` | Pure key — no hold-tap |
| Right mid | `SYM` layer | Pure `&mo` — opens symbols |
| Right outer | `HYPER` | Native ZMK macro (Ctrl+Alt+Gui+Shift) — used for AeroSpace |
 
 
## Combos
 
| Combo | Keys | Action | Notes |
|-------|------|--------|-------|
| NAV layer | Both mid thumbs | `&mo NAV` | 75ms timeout — chord both middle thumb keys |
| FN layer | `Q + P` | Toggle FN | Top row outer corners — deliberate |
| MEDIA layer | `Z + /` | Toggle MEDIA | Bottom row outer corners — deliberate |

All combos have a tight timeout (50–75ms) to prevent misfires during normal typing.

---

# Mappings and Layers
![Keymap](./keymap-drawer/eyelash_corne.svg)
