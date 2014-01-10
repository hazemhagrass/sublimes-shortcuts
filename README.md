sublimes-shortcuts
==================
Go to Prefrences->Key Bindings-User then add the following lines:

[

{ "keys": ["ctrl+t"], "command": "show_overlay", "args": {"overlay": "goto", "show_files": true} },

{ "keys": ["ctrl+tab"], "command": "next_view" },

{ "keys": ["ctrl+shift+tab"], "command": "prev_view" },


{ "keys": ["ctrl+pageup"], "command": "next_view_in_stack" },

{ "keys": ["ctrl+pagedown"], "command": "prev_view_in_stack" },


{ "keys": ["ctrl+l"], "command": "show_overlay", "args": {"overlay": "goto", "text": ":"} },


{ "keys": ["ctrl+d"], "command": "run_macro_file", "args": {"file": "Packages/Default/Delete Line.sublime-macro"} },


{ "keys": ["ctrl+h"], "command": "show_panel", "args": {"panel": "find_in_files"} },


{ "keys": ["alt+up"], "command": "swap_line_up" },

{ "keys": ["alt+down"], "command": "swap_line_down" },


{ "keys": ["ctrl+shift+o"], "command": "prompt_open_folder" },

{ "keys": ["ctrl+shift+alt+s"], "command": "save_all" },

{ "keys": ["ctrl+shift+alt+keypad_divide"], "command": "unfold_all" },

{ "keys": ["ctrl+shift+alt+keypad_multiply"], "command": "fold_all" },

{ "keys": ["ctrl+shift+alt+r"], "command": "reindent", "args": { "single_line": false } },

{ "keys": ["ctrl+shift+alt+l"], "command": "set_setting", "args": { "setting": "rulers", "value": [80, 120] }	}

]


sublimes-useful packages
==================
Those are some of the most usefull packages you can use in sublime (to install through the package manager):

"AdvancedNewFile"

"BracketHighlighter"

"CSSLint"

"Dayle Rees Color Schemes"

"Emmet"

"FileDiffs"

"HtmlTidy"

"Indent XML"

"jQuery"

"Meld diff"

"Move Tabs"

"SideBarEnhancements"

"SublimeCodeIntel"

"SublimeTODO"

"Tag"
