# Cupertino Light

A minimal, light syntax theme for Atom.

Every color was deliberately chosen to reduce eye strain while still maintaing high readability. Unlike most light themes, this one is easy on the eyes as opposed to making you feel like your eyes are going to burn up and fall out of their sockets.

For Visual Studio Code, I like [Alabaster](https://marketplace.visualstudio.com/items?itemName=tonsky.theme-alabaster) using the following modifications to match the colors in this theme:

Comments:                             #D4665D  
Strings:                              #4E7685  
Strings: Escape Sequences:            #8d938d  
Numbers, Characters:                  #20AB83  
Global definitions of entity names:   #288ad6  
Punctuation:                          #8d938d  

editor.background:                    #eceff0  
editor.lineHighlightBackground:       #eceff0  
panel.background:                     #dfe6e8  
sideBar.background:                   #dfe6e8  
activityBar.background:               #dfe6e8  
activityBar.foreground:               #288ad6  
editorLineNumber.foreground:          #8d938d  
editorCursor.foreground:              #596066  

Finally, add the following lines to tokenColors:

    {
        "name": "Function Call",
        "scope": [
            "meta.function-call.generic"
        ],
        "settings": {
            "foreground": "#108CB8"
        }
    },

![Screenshot](cupertino-light-scrot.jpg)
