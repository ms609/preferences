# positron

Delete local files and set up symlinks to this folder:
```powershell
New-Item -ItemType SymbolicLink -Path "$env:APPDATA\Positron\User\settings.json" -Target "C:\Users\<...>\GitHub\preferences\positron\settings.json"
New-Item -ItemType SymbolicLink -Path "$env:APPDATA\Positron\User\keybindings.json" -Target "C:\Users\<...>\GitHub\preferences\positron\keybindings.json"
```

Or copy [`keybindings.json`](https://raw.githubusercontent.com/ms609/preferences/main/positron/keybindings.json)
and [`settings.json`](https://raw.githubusercontent.com/ms609/preferences/main/positron/settings.json) to
`C:\Users\<User Name>\AppData\Roaming\Positron\User`
