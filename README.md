# dotfiles
To get the extension via a Powershell, use the following command:\
```bash
curl.exe -o extensions.json https://raw.githubusercontent.com/yatharth9/dotfiles/refs/heads/main/.vscode/extensions.md
```

To install VSC extensions, use any POSIX shell (Git Bash on Windows), and type the command:\
```bash
xargs -n1 code --install-extension < extensions.md
```
