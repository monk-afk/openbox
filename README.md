## rc.xml Keybinds
> Wn = Window Key

> Sh = Shift
#
### `--[[ Program Shortcuts ]]--`
```coffee
Thunar:		Wn + F
Terminal:	Wn + T
Codium:		Wn + E
Discord:	Wn + D
Geany:		Wn + G
Edit rc.xml:	Wn + F12
Reload Openbox:	Wn + Alt + F12
Open htop:	Wn + H
Lock Screen:	Wn + L
```
#
### `--[[ Window Tiling ]]--`
```coffee
"Toggle Maximize"
	Wn Alt:Up
"Layer to stack bottom (no minimize)"
	Wn Alt:Down
"Minimize and stack bottom"
	Wn Ctrl:Down
"Resize from edge right(alt) or left(ctrl)"
	Wn Alt:Left	# right shrink
	Wn Alt:Right	# right expand
	Wn Ctrl:Left	# left expand
	Wn Ctrl:Right	# left shrink
"Expand to next edge, or shrink if at screen border"
	Wn Left|Right|Up|Down
"Move to screen edge and resize to 70%"
	Wn Sh: Left|Right|Up|Down
"Move window to desktop"
	Alt Sh: Left|Right
"Cycle windows"
	Alt Tab:	# with menu
	Wn Tab:		# with preview
```
#
Bookmark http://openbox.org/wiki/Help:Bindings
