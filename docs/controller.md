# Controller config

If you're launching the game through Steam, you'll need to set up both the desktop and also game-specific configs, as the latter will apply when the game is in focus.

If you're not launching through Steam, then the desktop config will apply. For this reason, I prefer to add my non-Steam games to Steam and launch from there, so I can have customized controller configs per game.

Please learn how to change the controller config of games in Steam separately, I won't be covering that in this guide.

## Desktop vs game config

Game configs are per-game, and are active when the game is in focus. *You need to configure this for each game.* (Templates might help, see below.)

Desktop config is active when the game is *not* in focus.

As such, you'll want to ensure Alt+Tab is mapped for both configs, otherwise you may be able to tab away from the game but not back, or vice-versa.

## Example desktop config

For reference, this is some relevant mappings I have in my desktop controller config:

- L4 to Right Alt
- R4 to Tab  (so I can hold down Alt, then keep tabbing through open windows)
- R5 to Esc (to close Yomitan popup)
- D-pad left to mine word in Yomitan to Anki (Alt+E)
- D-pad right to replay Yomitan audio (Alt+P)
- D-pad up to go to page up through results (Alt+PgUp)
- D-pad down to go to page down through results (Alt+PgDn)

If you have a scan modifier key for Yomitan (it will only popup if the key is pressed), map that too. I leave mine to 'none' so it pops up on hover or if I tap on the touchscreen. `Alt` is a good choice for scan modifier key as it should already be mapped to a button for our alt-tab usage.

Refer to the [Yomitan docs](https://github.com/themoeway/yomitan/blob/master/docs/keyboard-shortcuts.md) for more shortcut keys you might be interested to use and map those if you want.

## Example game config

For VNs, you'll likely want to map these actions if it's not already in your config:

- replay audio
- bring up backlog
- quick save, quick load

If you're mining, also remember to map the keys for capturing screenshots and recording audio.

## Tips

For some reason left Alt+Tab doesn't work for me to tab away from game. But Right Alt+Tab does.
Personally I map Right Alt to L4, and Tab to R4. This way, I can keep holding Alt while tabbing a few times to swap between multiple windows, instead of just toggling between the 2 most recent.

If you're using SteamTinkerLaunch, you'll want to ensure something (I suggest touchpad) is mapped to mouse movement and click in the game config so that you can click on the menu. Or, you can use the touch screen or an external mouse when configuring SteamTinkerLaunch for your game.

Steam + x will bring up the on-screen keyboard.

## Templates

(WIP) It should be possible to save a config as a template to make it easier to set up for other games, but I have not done this yet.

## Advanced mappings

Examples of more fancy things you can do:

- set up different layers so the same button does different things when another button or the touchpad is pressed.
- create radial menus with the touchpad or stick
- create button menus with the touchpad

These are useful if the game you're playing is already using the majority of buttons and you want to map more actions for Anki mining.

You can learn more from video tutorials, eg. [NerdNest's excellent one on action layers](https://youtu.be/nEh79r93vYY).
