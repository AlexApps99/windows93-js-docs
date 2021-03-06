---
title: Windows 93 JS
layout: default
---

# BIOS
## `$boot`
```js
{
  "BIOS":      {},    // Div of BIOS itself
  "BOOTLOG":   {},    // Div of BIOS log (which apps are ready, etc)
  "BIOSERROR": {},    // TODO
  "TOOLONG":   {},    // Div that appears if boot takes too long
  "REINSTALL": {},    // Div that asks if W93 should be reinstalled
  "VERSION": "2.3.9", // W93 Version
  "hasError": false   // TODO
}
```

## `biosSetup()`
Ran at boot, used to initialise the BIOS screen


# Undocumented
## `$error(ex)`
Seems to be for the old bug report system, stack trace

## `saveAs(e, t)`
Used by `$file.download`, to save a file from W93 to disk

## `$noop(n)`
Empty function

## `$watch(c)`
TODO

## `$url`
Functions about Windows93-related URLs

## `$maxZ(e, n)`
TODO

## `$chain()`
Seems to be used in `$log`, TODO

## `$undo(n)`
TODO

## `$loop(e, t)`
TODO

## `system42(e, n)`
TODO

## `$delegate(r, o)`
TODO

## `$io`
TODO

## `$kernel(e, n)`
TODO

## `$route(e)`
TODO

## `$fullscreen(e, n)`
TODO

## `$animate(n, t, o)`
TODO

## `$state`
TODO

## `$selection`
TODO

## `$ajax(e, t, n, r)`
TODO

## `$db(o, t, e)`
TODO

## `$store(t, n, o, e)`
TODO

## `$el(a, e)`
TODO

## `$on`
TODO

## `$extend(t)`
TODO

## `$screenshot(d, e, f)`
TODO

## `$socket(n)`
TODO

## `$template(n)`
TODO

## `$archive(i, s)`
TODO

## `$key(e)`
TODO

## `$gamepad(n)`
Unused, currently just logs `n` to console

## `$wheel(s, e, t)`
TODO

## `$log(e, t, o)`
TODO

## `$cli(e, t)`
TODO

## `$box(e, o, t)`
TODO

## `$drag(i, s, e)`
TODO

## `$transition(e)`
TODO

## `$pos(f, t)`
TODO

## `$resize(e, t)`
TODO

## `$notif(e, t)`
TODO

## `$menu(i, e, t)`
TODO

## `$form(e, t)`
TODO

## `$window(e)`
TODO

## `$alert(n, t)`
TODO

## `$confirm(e, n)`
TODO

## `$prompt(o, e, i)`
TODO

## `$fs`
TODO

## `$file`
TODO

## `$loader(n, o)`
TODO

## `le`
TODO

## `$editor(a, e)`
TODO

## `$audio(n, o)`
TODO

## `$exe(t, e, i)`
TODO

## `$explorer(o, e, t)`
TODO


# External libraries
## `platform`
Provided by [platform.js](https://github.com/bestiejs/platform.js/blob/master/doc/README.md#readme)

## `localforage`
Provided by [localForage](https://localforage.github.io/localForage/#data-api)

## `Howler`
Provided by [howler.js](https://github.com/goldfire/howler.js#documentation)

## `Howl`
Provided by [howler.js](https://github.com/goldfire/howler.js#documentation)
