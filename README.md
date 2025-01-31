# VS Code | List Keyboard Shortcuts, Plugins & Snippets

For HTML, CSS, JavaScript, ReactJS, VueJS

[VSCode] is a popular code editor for HTML, CSS, SCSS, JS and other programming languages.
Using plugins the editor can be turned into a powerful environment for developing applications and websites.

## VS Code Editor Keyboard Shortcuts

- **[Windows]**
- **[MacOS]**
- **[Linux]**

[windows]: https://github.com/GrafSoul/vscode-plugins/blob/master/doc/keyboard-shortcuts-windows.pdf
[macos]: https://github.com/GrafSoul/vscode-plugins/blob/master/doc/keyboard-shortcuts-macos.pdf
[linux]: https://github.com/GrafSoul/vscode-plugins/blob/master/doc/keyboard-shortcuts-linux.pdf

## Editor Settings

Place the code in the settings.json file and place it in the .vscode folder in the project root.

```javascript
{
  "workbench.colorCustomizations": {
    "titleBar.activeForeground": "#c8c8c8",
    "titleBar.inactiveForeground": "#c8c8c8",
    "titleBar.activeBackground": "#1c2646",
    "titleBar.inactiveBackground": "#1c2646",
    "terminal.background":"#181818",
    "terminal.foreground":"#d8d8d8",
    "terminalCursor.background":"#d8d8d8",
    "terminalCursor.foreground":"#d8d8d8",
    "terminal.ansiBlack":"#181818",
    "terminal.ansiBlue":"#7cafc2",
    "terminal.ansiBrightBlack":"#585858",
    "terminal.ansiBrightBlue":"#7cafc2",
    "terminal.ansiBrightCyan":"#86c1B9",
    "terminal.ansiBrightGreen":"#a1b56c",
    "terminal.ansiBrightMagenta":"#ba8baf",
    "terminal.ansiBrightRed":"#ab4642",
    "terminal.ansiBrightWhite":"#f8f8f8",
    "terminal.ansiBrightYellow":"#f7ca88",
    "terminal.ansiCyan":"#86c1b9",
    "terminal.ansiGreen":"#a1b56c",
    "terminal.ansiMagenta":"#ba8baf",
    "terminal.ansiRed":"#ab4642",
    "terminal.ansiWhite":"#d8d8d8",
    "terminal.ansiYellow":"#f7ca88"
  },
  "editor.formatOnSave": true,
  "[javascript]": {
    "editor.formatOnSave": true
  },
  "[javascriptreact]": {
    "editor.formatOnSave": true
  },
  "eslint.alwaysShowStatus": true,
  "editor.codeActionsOnSave": {
    "source.fixAll": true
  },
  "prettier.disableLanguages": [""],
}
```

## Useful Plugins

### Code Style

- **[All Autocomplete]** - Create autocomplete items from open files in VSCode.
- **[Auto Close Tag]** - Automatically add HTML/XML close tag, same as Visual Studio IDE or Sublime Text.
- **[Auto Complete Tag]** - Extension Packs to add close tag and rename paired tag automatically for HTML/XML.
- **[Auto Rename Tag]** - Auto rename paired HTML/XML tag.
- **[Beautify]** - Beautify code in place for VS Code.
- **[Prettier]** - Code formatter using prettier.
- **[Code Spell Checker]** - Spelling checker for source code.
- **[Code Runner]** Run code snippet or code file for multiple languages.
- **[Indent Rainbow]** - Makes indentation easier to read.
- **[Bracket Pair Colorizer]** - A customizable extension for colorizing matching brackets.
- **[Path Intellisense]** - Visual Studio Code plugin that autocompletes filenames
- **[Styled Components]** - Syntax highlighting for styled-components

### Git

- **[GitLens — Git supercharged]** - Supercharge the Git capabilities built into Visual Studio Code.

### NPM

- **[Version Lens]** - Shows the latest version for each package using code lens.
- **[Import Cost]** - Display import/require package size in the editor.

### Deno

- **[Deno]** - Deno support for VSCode.
- **[deno-vscode]** - A deno extension for vscode to make it easier for developers.

### Useful

- **[WakaTime]** - Metrics, insights, and time tracking automatically generated from your programming activity.
- **[Polacode]** - Polaroid for your code.
- **[Vscode Google Translate]** - Translate text right in your code.
- **[Path Autocomplete]** - Provides path completion for visual studio code.
- **[Lorem ipsum]** - Generates and inserts lorem ipsum text.
- **[Live Server]** - Launch a development local Server with live reload feature for static & dynamic pages.
- **[Multiple clipboards for VSCode]** - Override the regular Copy and Cut commands to keep selections in a clipboard ring.
- **[Debugger for Chrome]** - Debug your JavaScript code in the Chrome browser, or any other target that supports the Chrome Debugger protocol. Trouble Installing?
- **[Project Manager]** - Easily switch between projects.
- **[Settings Sync]** - Synchronize Settings, Snippets, Themes, File Icons, Launch, Keybindings, Workspaces and Extensions Across Multiple Machines Using GitHub Gist.
- **[Turbo Console Log]** - SAutomating the process of writing meaningful log messages.
- **[VScode Backup]** - Backup/Restore VSCode Settings and plugins.

### JavaScript

- **[jsflowchart]** - JS Flowchart in Real-time.
- **[Hyper JavaScript Snippets]** - A collection of snippets that cover JavaScript, TypeScript, and NodeJS for Visual Studio Code.
- **[JavaScript (ES6) code snippets]** - Code snippets for JavaScript in ES6 syntax.
- **[ES7 React/Redux/GraphQL/React-Native Snippets]** - Simple extensions for React, Redux and Graphql in JS/TS with ES7 syntax.
- **[React code snippets]** - Code snippets for Reactjs development in ES6 syntax.
- **[Vue 3 Snippets]** - This extension adds Vue 3 and Vue 2 Code Snippets into Visual Studio Code.
- **[Babel JavaScript]** - VSCode syntax highlighting for today's JavaScript, ported from gandm's language-babel for Atom.
- **[jQuery Code Snippets]** - Over 130 jQuery Code Snippets.
- **[ESLint]** - Integrates ESLint JavaScript into VS Code.
- **[Quokka]** - Live Scratchpad for JavaScript.

### TypeScript

- **[TSLint]** - TSLint support for Visual Studio Code.

### GraphQL

- **[GraphQL]** - GraphQL extension for VSCode adds syntax highlighting, validation, and language features like go to definition, hover information and autocompletion for graphql projects. This extension also works with queries annotated with gql tag.
- **[Apollo GraphQL]** - Rich editor support for GraphQL client and server development that seamlessly integrates with the Apollo platform.
- **[GraphQL for VSCode]** - GraphQL syntax highlighting, linting, auto-complete, and more!.

### CSS & PreCSS

- **[Sass]** - Indented Sass syntax Highlighting, Autocomplete & Formatter.
- **[Live Sass Compiler]** - Compile Sass or Scss to CSS at realtime with live browser reload.
- **[SCSS IntelliSense]** - Advanced autocompletion and refactoring support for SCSS.
- **[SCSS Formatter]** - Advanced autocompletion and refactoring support for SCSS.
- **[CSS Navigation]** - Allows Go to Definition from HTML to CSS; provides Completion and Workspace Symbols for class & id name; supports CSS, Sass, Less languages.
- **[eCSStractor]** - Extracting selectors from HTML and generate CSS stylesheet.

### BEM

- **[BEM Helper]** - Improve writing html using BEM naming conventions.
- **[SCSS BEM Support]** - BEM support for SCSS files.

### Pug

- **[Pug]** - Pug/Jade Snippets for VSCode.
- **[Live Pug Compiler]** - Compile Pug to HTML at realtime with live browser reload.

### Images

- **[Image preview]** - Shows image preview in the gutter and on hover.
- **[SVG]** - SVG Coding, Minify, Pretty, Preview All-In-One.

### Fonts

- **[Google Fonts]** - Allows you to browse and insert Google Fonts <link> or @import !.
- **[SVG Font Previewer]** - Show the SVG font details, icons, icon name and icon unicode as hexadecimal value. It can also preview any valid SVG file.

### TODO

- **[TODO Highlight]** - Highlight TODOs, FIXMEs, and any keywords, annotations...
- **[Better Comments]** - Improve your code commenting by annotating with alert, informational, TODOs, and more!

### Themes

- **[Theme - Oceanic Next]** - Oceanic Next theme for VSCode + dimmed bg version for better looking UI.
- **[vscode-icons]** - Icons for Visual Studio Code.

### File Converters

- **[Markdown PDF]** - This extension converts Markdown files to pdf, html, png or jpeg files.

## MJML for Emails

- **[MJML]** - MJML preview, lint, compile for Visual Studio Code.
- **[MJML Snippets]** - MJML Snippets for Virtual Studio Code.

### PDF

- **[vscode-pdf]** - Display pdf file in VSCode.

[vscode]: https://code.visualstudio.com/
[all autocomplete]: https://marketplace.visualstudio.com/items?itemName=Atishay-Jain.All-Autocomplete
[auto close tag]: https://marketplace.visualstudio.com/items?itemName=formulahendry.auto-close-tag
[auto complete tag]: https://marketplace.visualstudio.com/items?itemName=formulahendry.auto-close-tag
[auto rename tag]: https://marketplace.visualstudio.com/items?itemName=formulahendry.auto-rename-tag
[beautify]: https://marketplace.visualstudio.com/items?itemName=HookyQR.beautify
[prettier]: https://marketplace.visualstudio.com/items?itemName=esbenp.prettier-vscode
[code runner]: https://marketplace.visualstudio.com/items?itemName=formulahendry.code-runner
[gitlens — git supercharged]: https://marketplace.visualstudio.com/items?itemName=eamodio.gitlens
[version lens]: https://marketplace.visualstudio.com/items?itemName=pflannery.vscode-versionlens&wt.mc_id=vscode-versionlens-github-vscode-contrib
[import cost]: https://marketplace.visualstudio.com/items?itemName=wix.vscode-import-cost
[path autocomplete]: https://marketplace.visualstudio.com/items?itemName=christian-kohler.path-intellisense
[live server]: https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer
[multiple clipboards for vscode]: https://github.com/stef-levesque/vscode-multiclip
[javascript (es6) code snippets]: https://marketplace.visualstudio.com/items?itemName=xabikos.JavaScriptSnippets
[es7 react/redux/graphql/react-native snippets]: https://marketplace.visualstudio.com/items?itemName=dsznajder.es7-react-js-snippets
[react code snippets]: https://marketplace.visualstudio.com/items?itemName=xabikos.ReactSnippets
[vue 3 snippets]: https://marketplace.visualstudio.com/items?itemName=Wscats.vue
[babel javascript]: https://marketplace.visualstudio.com/items?itemName=mgmcdermott.vscode-language-babel
[eslint]: https://marketplace.visualstudio.com/items?itemName=dbaeumer.vscode-eslint
[sass]: https://marketplace.visualstudio.com/items?itemName=Syler.sass-indented
[quokka]: https://marketplace.visualstudio.com/items?itemName=WallabyJs.quokka-vscode
[todo highlight]: https://marketplace.visualstudio.com/items?itemName=wayou.vscode-todo-highlight
[indent rainbow]: https://marketplace.visualstudio.com/items?itemName=oderwat.indent-rainbow
[bracket pair colorizer]: https://marketplace.visualstudio.com/items?itemName=CoenraadS.bracket-pair-colorizer
[lorem ipsum]: https://marketplace.visualstudio.com/items?itemName=Tyriar.lorem-ipsum
[theme - oceanic next]: https://marketplace.visualstudio.com/items?itemName=naumovs.theme-oceanicnext
[vscode-icons]: https://marketplace.visualstudio.com/items?itemName=vscode-icons-team.vscode-icons
[markdown pdf]: https://marketplace.visualstudio.com/items?itemName=yzane.markdown-pdf
[vscode-pdf]: https://marketplace.visualstudio.com/items?itemName=tomoki1207.pdf
[hyper javascript snippets]: https://marketplace.visualstudio.com/items?itemName=t7yang.hyper-javascript-snippets
[code spell checker]: https://marketplace.visualstudio.com/items?itemName=streetsidesoftware.code-spell-checker
[live sass compiler]: https://marketplace.visualstudio.com/items?itemName=ritwickdey.live-sass
[scss intellisense]: https://marketplace.visualstudio.com/items?itemName=mrmlnc.vscode-scss
[scss formatter]: https://marketplace.visualstudio.com/items?itemName=sibiraj-s.vscode-scss-formatter
[better comments]: https://marketplace.visualstudio.com/items?itemName=aaron-bond.better-comments
[bem helper]: https://marketplace.visualstudio.com/items?itemName=Box-Of-Hats.bemhelper
[ecsstractor]: https://marketplace.visualstudio.com/items?itemName=kubosho.ecsstractor
[css navigation]: https://marketplace.visualstudio.com/items?itemName=pucelle.vscode-css-navigation
[image preview]: https://marketplace.visualstudio.com/items?itemName=kisstkondoros.vscode-gutter-preview
[debugger for chrome]: https://marketplace.visualstudio.com/items?itemName=msjsdiag.debugger-for-chrome
[vscode google translate]: https://marketplace.visualstudio.com/items?itemName=funkyremi.vscode-google-translate
[project manager]: https://marketplace.visualstudio.com/items?itemName=alefragnani.project-manager
[settings sync]: https://marketplace.visualstudio.com/items?itemName=Shan.code-settings-sync
[scss bem support]: https://marketplace.visualstudio.com/items?itemName=joloyonaha.scss-bem-support
[svg]: https://marketplace.visualstudio.com/items?itemName=jock.svg
[svg font previewer]: https://marketplace.visualstudio.com/items?itemName=nkokhelox.svg-font-previewer
[jquery code snippets]: https://marketplace.visualstudio.com/items?itemName=donjayamanne.jquerysnippets
[jsflowchart]: https://marketplace.visualstudio.com/items?itemName=MULU-github.jsflowchart
[pug]: https://marketplace.visualstudio.com/items?itemName=amandeepmittal.pug
[live pug compiler]: https://marketplace.visualstudio.com/items?itemName=jaheenafsarsyed.live-pug-compiler
[google fonts]: https://marketplace.visualstudio.com/items?itemName=lior-chamla.google-fonts
[wakatime]: https://marketplace.visualstudio.com/items?itemName=WakaTime.vscode-wakatime
[turbo console log]: https://marketplace.visualstudio.com/items?itemName=ChakrounAnas.turbo-console-log
[polacode]: https://marketplace.visualstudio.com/items?itemName=pnp.polacode
[apollo graphql]: https://marketplace.visualstudio.com/items?itemName=apollographql.vscode-apollo
[graphql]: https://marketplace.visualstudio.com/items?itemName=GraphQL.vscode-graphql
[graphql for vscode]: https://marketplace.visualstudio.com/items?itemName=kumar-harsh.graphql-for-vscode
[path intellisense]: https://marketplace.visualstudio.com/items?itemName=christian-kohler.path-intellisense
[tslint]: https://marketplace.visualstudio.com/items?itemName=ms-vscode.vscode-typescript-tslint-plugin
[mjml]: https://marketplace.visualstudio.com/items?itemName=attilabuti.vscode-mjml
[mjml snippets]: https://marketplace.visualstudio.com/items?itemName=kvnol.mjml-snippets
[deno]: https://marketplace.visualstudio.com/items?itemName=denoland.vscode-deno
[deno-vscode]: https://marketplace.visualstudio.com/items?itemName=ameerthehacker.deno-vscode
[vscode backup]: https://marketplace.visualstudio.com/items?itemName=westenets.vscode-backup
[styled components]: https://marketplace.visualstudio.com/items?itemName=jpoissonnier.vscode-styled-components

## Snippets in PDF files

- **[Emmet - A5]** and **[Emmet- A4]** sheet formats
- **[JavaScript (ES6) code]**
- **[ES7 React/Redux/GraphQL/React-Native]**
- **[React code]**
- **[Vue 3]**

[emmet - a5]: https://github.com/GrafSoul/vscode-plugins/blob/master/doc/keyboard-shortcuts-emmet-a5.pdf
[emmet- a4]: https://github.com/GrafSoul/vscode-plugins/blob/master/doc/keyboard-shortcuts-emmet-a4.pdf
[javascript (es6) code]: https://github.com/GrafSoul/vscode-plugins/blob/master/doc/keyboard-shortcuts-es6.pdf
[es7 react/redux/graphql/react-native]: https://github.com/GrafSoul/vscode-plugins/blob/master/doc/keyboard-shortcuts-es7.pdf
[react code]: https://github.com/GrafSoul/vscode-plugins/blob/master/doc/keyboard-shortcuts-react.pdf
[vue 3]: https://github.com/GrafSoul/vscode-plugins/blob/master/doc/keyboard-shortcuts-vue3.pdf

© 2020
