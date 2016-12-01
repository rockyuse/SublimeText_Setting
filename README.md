# Sublime Text Setting

####Preferences  Settings - User 添加以下内容：
{
    "color_scheme": "Packages/Color Scheme - Default/Mac Classic.tmTheme",
    "font_face": "Courier New",
    "font_size": 9.0
}

####Preferences  Key Bindings - Default 修改ctrl+d的内容为：
{ "keys": ["ctrl+d"], "command": "run_macro_file", "args": {"file": "Packages/Default/Delete Line.sublime-macro"} },

####Mac 快捷键
[
	{ "keys": ["ctrl+d"], "command": "run_macro_file", "args": {"file": "res://Packages/Default/Delete Line.sublime-macro"} },
	{ "keys": ["ctrl+s"], "command": "save" },
	{ "keys": ["ctrl+x"], "command": "cut" },
	{ "keys": ["ctrl+c"], "command": "copy" },
	{ "keys": ["ctrl+v"], "command": "paste" },
	{ "keys": ["ctrl+z"], "command": "undo" },
	{ "keys": ["ctrl+r"], "command": "redo_or_repeat" },

	{ "keys": ["ctrl+super+c"], "command": "cancel_build" },
	{ "keys": ["ctrl+shift+d"], "command": "duplicate_line" },

	{ "keys": ["ctrl+f"], "command": "show_panel", "args": {"panel": "find", "reverse": false} },
	{ "keys": ["super+ctrl+h"], "command": "show_panel", "args": {"panel": "find_in_files"} },
	{ "keys": ["super+ctrl+f"], "command": "show_panel", "args": {"panel": "replace", "reverse": false} }
]

