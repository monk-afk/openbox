## rc.xml Keybinds
- Wn = Window Key
- Sh = Shift
### `--[[ Program Shortcuts ]]--`
```coffee
Run Dialog:	Alt + F2|F3
Browser:	Wn + W
Terminal:	Wn + T
Codium:		Wn + E
Discord:	Wn + D
Music:		Wn + M
Volume:		Wn + V
Geany:		Wn + G
Thunar:		Wn + F
htop:		Wn + H

Edit rc.xml:	Wn + F12
Reload Openbox:	Wn + Alt + F12

Sleep Session:	Wn + S
Logout User:	Wn + X
Lock Screen:	Wn + L
```

### `--[[ Window Tiling ]]--`
```coffee
"Toggle Maximize"
	Ctrl Alt:Up
"Layer to stack bottom (no minimize)"
	Ctrl Alt:Down
"Minimize and stack bottom"
	Ctrl Alt:M

"Resize edge right/top(alt) or left/bottom(ctrl)"
	Wn Alt:Left|Right	# right: shrink|expand
	Wn Alt:Down|Up	# top: shrink|expand
	Wn Ctrl:Left|Right	# left: expand|shrink
	Wn Ctrl:Down|Up	# bottom: expand|shrink
"Expand to next edge, or shrink if at screen border"
	Wn Left|Right|Up|Down
"Move to screen edge and resize to 70%"
	Wn Sh: Left|Right|Up|Down

"Move window to desktop"
	Alt Sh: Left|Right
"Switch to desktop"
	Ctl Alt: Left|Right
"Cycle windows"
	Alt Tab:	# with menu
	Wn Tab:		# with preview
```

Bookmark http://openbox.org/wiki/Help:Bindings