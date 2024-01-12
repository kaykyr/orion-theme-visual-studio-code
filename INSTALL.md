---
runme:
  id: 01HKYZ872SFA8TY2M6PRYCHSMT
  version: v2.2
---

### [Visual Studio Code](https://code.visualstudio.com/)

#### Install using Command Palette

1. Go to `View -> Command Palette` or press `Ctrl+Shift+P`
2. Then enter `Install Extension`
3. Write `Orion Theme`
4. Select it or press Enter to install

#### Install using Git

If you are a git user, you can install the theme and keep up to date by cloning the repo:

```bash {"id":"01HKYZ872SFA8TY2M6PNNH7JBT"}
git clone https://github.com/kaykyr/orion-theme-visual-studio-code.git ~/.vscode/extensions/theme-orion
cd ~/.vscode/extensions/theme-orion
npm install
npm run build
```

#### Activating theme

Run Visual Studio Code. The Orion Syntax Theme will be available from `File -> Preferences -> Color Theme` dropdown menu.
