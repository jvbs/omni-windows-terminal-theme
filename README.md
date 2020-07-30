# Omni for Windows Terminal

## Install
Open Windows Terminal and click on the down arrow icon, and then settings option.

This action will open a file named `settings.json`.

In the `settings.json`, find the schemes section and paste the content bellow.

```json
    "schemes": [
        {
            "name" : "Omni",
            "cursorColor": "#f8f8f2",
            "selectionBackground": "#f8f8f2",
            
            "background" : "#191622",
            "foreground" : "#E1E1E6",

            "black" : "#000000",
            "blue" : "#bd93f9",
            "cyan" : "#8d79ba",
            "green" : "#50fa7b",
            "purple" : "#ff79c6",
            "red" : "#FF5555",
            "white" : "#F8F8F2",
            "yellow" : "#effa78",
            "brightBlack" : "#4d4d4d",
            "brightBlue" : "#caa9fa",
            "brightCyan" : "#aa91e3",
            "brightGreen" : "#5af78e",
            "brightPurple" : "#FF92DF",
            "brightRed" : "#ff6e67",
            "brightWhite" : "#F8F8F2",
            "brightYellow" : "#eaf08d"
        }
    ],
```

## Activate
Once the color scheme has been defined, it's time to enable it. Find the profiles section and add a colorScheme value to the default profile.

```json
"profiles": {
    "defaults": {
        "colorScheme" : "Omni"
    }
}
```
