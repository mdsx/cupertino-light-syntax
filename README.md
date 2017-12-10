# Cupertino Light

A minimal, light syntax theme for Atom.

Most light themes are white. Ones that respect your eyes are beige. This one is more like metal, and it's easy on the eyes too.

For Visual Studio Code, I like [Alabaster](https://marketplace.visualstudio.com/items?itemName=tonsky.theme-alabaster) using the following modifications to match the colors in this theme:

    { "$schema": "vscode://schemas/color-theme",
      "name": "Alabaster",
      "tokenColors": [
        { "name": "Comments",
    			"scope": [
    				"comment",
    				"punctuation.definition.comment"
    			],
    			"settings": {
    				"foreground": "#D4665D"
    			}
    		},
    		{ "name": "Strings",
    			"scope": [
    				"string",
    				"string.regexp",
    				"constant.other.symbol"
    			],
    			"settings": {
    				"foreground": "#4E7685"
    			}
    		},
    		{
    			"name": "Strings: Escape Sequences",
    			"scope": "constant.character.escape",
    			"settings": {
    				"foreground": "#8d938d"
    			}
    		},
    		{
    			"name": "Numbers, Characters",
    			"scope": [
    				"constant.numeric",
    				"constant.character",
    				"constant.keyword",
    				"constant"
    			],
    			"settings": {
    				"foreground": "#20AB83"
    			}
    		},
    		{
    			"name": "Global definitions of entity names",
    			"scope": "entity.global",
    			"settings": {
    				"foreground": "#288ad6"
    			}
    		},
    		{
    			"name": "Function Call",
    			"scope": [
    				"meta.function-call.generic"
    			],
    			"settings": {
    				"foreground": "#108CB8"
    			}
    		},
    		{
    			"name": "Punctuation",
    			"scope": "punctuation",
    			"settings": {
    				"foreground": "#8d938d"
    			}
    		},
    		{
    			"name": "Invalid",
    			"scope": "invalid",
    			"settings": {
    				"background": "#96000014",
    				"foreground": "#660000"
    			}
    		},
    		{
    			"name": "Extra: Diff Range",
    			"scope": [
    				"meta.diff.range",
    				"meta.diff.index",
    				"meta.separator"
    			],
    			"settings": {
    				"background": "#DDDDFF",
    				"foreground": "#434343"
    			}
    		},
    		{
    			"name": "Extra: Diff From",
    			"scope": "meta.diff.header.from-file",
    			"settings": {
    				"background": "#FFDDDD",
    				"foreground": "#434343"
    			}
    		},
    		{
    			"name": "Extra: Diff To",
    			"scope": "meta.diff.header.to-file",
    			"settings": {
    				"background": "#DDFFDD",
    				"foreground": "#434343"
    			}
    		}
      ],
    	"colors": {
    		"editor.background": "#eceff0",
    		"editor.lineHighlightBackground": "#eceff0",
    		"editor.selectionBackground": "#BFDBFE",
    		"editor.selectionHighlightBackground": "#E0E0E0",
    		"panel.background": "#dbe1e3 ",
    		"sideBar.background": "#dbe1e3",
    		"activityBar.background": "#dbe1e3",
    		"activityBar.foreground": "#288ad6",
    		"editorLineNumber.foreground": "#8d938d",
    		"editorCursor.foreground": "#596066",
    		"editor.findMatchBackground": "#FFBC5D",
    		"editor.findMatchHighlightBackground": "#FFE9A6",

    		"terminal.ansiWhite": "#BBBBBB",
        "terminal.ansiBlack": "#000000",
        "terminal.ansiBlue": "#325CC0",
        "terminal.ansiCyan": "#0083B2",
        "terminal.ansiGreen": "#448C27",
        "terminal.ansiMagenta": "#7A3E9D",
        "terminal.ansiRed": "#AA3731",
        "terminal.ansiYellow": "#FFBC5D",
        "terminal.ansiBrightWhite": "#FFFFFF",
        "terminal.ansiBrightBlack": "#777777",
        "terminal.ansiBrightBlue": "#007ACC",
        "terminal.ansiBrightCyan": "#00AACB",
        "terminal.ansiBrightGreen": "#60CB00",
        "terminal.ansiBrightMagenta": "#E64CE6",
        "terminal.ansiBrightRed": "#F05050",
        "terminal.ansiBrightYellow": "#FFD9A6"
      }
    }

![Screenshot](cupertino-light-scrot.jpg)
