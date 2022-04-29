# MS Word

1. Copy [`Normal.dotm`](https://raw.githubusercontent.com/ms609/preferences/main/Word/Normal.dotm) to `%APPDATA%/Microsoft/Templates`.

1. Right-click the ribbon, then use "Customize the ribbon" → "Import / Export"
and select `Toolbar.exportedUI`.

1. Copy [`WORDLIST.DIC`](https://raw.githubusercontent.com/smithlabdurham/dictionary/main/WORDLIST.dic) to `%APPDATA%/Microsoft/UProof`.

1. `regedit` to set registry keys:
  - `HKEY_CURRENT_USER\Software\Microsoft\Office\16.0\Common\SignIn`: New DWORD value `SignInOptions = 3`.

[Migrate other settings](https://superuser.com/questions/543012/how-to-migrate-microsoft-office-settings)
