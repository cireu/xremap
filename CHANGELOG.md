## v0.2.3

* Detect XWayland applications properly for Sway
  [#65](https://github.com/k0kubun/xremap/pull/65)

## v0.2.2

* Support `BTN_MISC`, `BTN_MOUSE`, `BTN_EXTRA`, `BTN_FORWARD`, `BTN_BACK`, and `BTN_TASK`
  as mouse buttons as well
  [#63](https://github.com/k0kubun/xremap/pull/63)

## v0.2.1

* Support remapping a mouse with `BTN_SIDE`
  [#57](https://github.com/k0kubun/xremap/pull/57)

## v0.2.0

* Support left/right-specific modifiers by `_L`/`_R` prefixes
  [#56](https://github.com/k0kubun/xremap/pull/56)

## v0.1.9

* Fix a bug of handling control keys inside `with_mark` of v0.1.7
  [#55](https://github.com/k0kubun/xremap/pull/55)

## v0.1.8

* Add `--version` option to show xremap's version
  [#54](https://github.com/k0kubun/xremap/issues/54)

## v0.1.7

* Add `set_mark` and `with_mark` to emulate Emacs's mark mode
  [#53](https://github.com/k0kubun/xremap/issues/53)

## v0.1.6

* Add `launch` action to execute a command
  [#52](https://github.com/k0kubun/xremap/issues/52)

## v0.1.5

* Add `--watch` option to automatically add new devices
* Avoid crashing on a disconnected device
* `name` is made optional in `modmap` and `keymap`

## v0.1.4

* Add `--ignore` option to deny-list devices instead of allow-listing them
  [#46](https://github.com/k0kubun/xremap/issues/46)
* Abort `xremap` when no device was selected

## v0.1.3

* Support remapping a key to two different keys depending on
  whether it's pressed alone or held
  [#47](https://github.com/k0kubun/xremap/issues/47)

## v0.1.2

* Fix recognition of a right Alt modifier in `keymap`
  [#43](https://github.com/k0kubun/xremap/issues/43)

## v0.1.1

* Binary distribution is built on GitHub Actions
* Improve error message for features `gnome` and `sway`
* Stop using a fork of swayipc and publish `sway` feature on crates.io

## v0.1.0

* Initial release
  * `modmap`, `keymap`, `application`, `remap`
  * --features: `x11`, `gnome`, `sway`
