
# VStorm Pack

Includes the most important extensions to get you started with PHP development in Visual Studio Code


#### Shortcuts

    Command Mode = Ctrl + Shift + p 
    Focuses on Explorer = ctrl + 0
    Move Selected Lines = alt + up / down
    Hide tree view = Ctrl + B 

    Explorer  = Ctrl + shift + E
    Version Control (Git)  = Ctrl + shift + v
    Search = Ctrl + shift + f 
    Debugger = ctrl + shift + d
    Extensions  = Ctrl + shift + x

    Key Binding  = Ctrl + K + S 
    Setting = Ctrl + ,  
    Terminal = Ctrl + ~ 
    Go to Line = ctrl + G  | ctrl + p ---> type :
    Split Screen = Ctrl+\   (switch between them ctrl+1 , ctrl+2 , ...)

    Select current line = Ctrl+L
    Select All Occurrences of selected word = crtl + shift + L
    Select Match To Selected Text = Ctrl + d (for next one one again press ctrl + d)
    Multiple Cursor: alt + mouse left

    Next or Previous Method or Tag = ctrl + up arrow key Or down arrow key
    File All References = alt + shift + F12
    Go to Symbol in File = ctrl + shift + O  | | ctrl + p ---> type @
    Go to Symbol in Workspace = Ctrl + T
    Go to Implementation = ctrl + F12
    Peek = shift + F12

    Expand Selection =  Shift+Alt+Left or Shift+Alt+Right
    Code Folding = Ctrl+Shift+[ OR  Ctrl+Shift+]
    Line Height = crtl + ,  ---> search for line Height then -----> set to 40
    Open Markdown preview = Ctrl + Shift + V

    Duplicate Line Up = Ctrl + Alt + Shift + 8
    Duplicate Line Down : Ctrl + Alt + Shift + 2
    Delete Line: Ctrl + Shift + K 

    Code Formatting:
        Ubuntu = Ctrl + Shift + I
        Windows = Shift + Alt + F
        MacOS = Shift + Option + 

    Change Workspace = ctrl + r    

    List of all files open in an editor group: ctrl + tab
    Focus Breadcrumbs =  ctrl + shift + . 
    Bracket matching = Ctrl + Shift + \
    Switch to previous open file = ctrl + p + ctrl + p
    Open Reference = ctrl + shift + mouse left
    Goto Previous Edit point = ctrl + alt + -
    Shrink/expand selection = Shift+Alt+Right or Shift+Alt+LEFT
    Column (box) selection = Place the cursor in one corner and then hold Shift+Alt while dragging to the opposite corner

#### user settings

```json
    {
        "workbench.iconTheme": "eq-material-theme-icons",
        "window.zoomLevel": 0,
        "materialTheme.autoApplyIcons": true,
        "workbench.colorTheme": "Material Theme",
        "materialTheme.fixIconsRunning": false,
        "gitlens.advanced.messages": {
            "suppressFileNotUnderSourceControlWarning": true,
            "suppressShowKeyBindingsNotice": true
        },
        "editor.quickSuggestions": {
            "comments": true
        },
        "sync.forceUpload": false,
        "sync.autoUpload": true,
        "php.suggest.basic": false,
        "[php]": {
            "editor.defaultFormatter": "bmewburn.vscode-intelephense-client"
        },
        "sqltools.connections": [],
        "yaml.schemas": {},
        "atlascode.jira.jqlList": [],
        "atlascode.jira.enabled": true,
        "files.autoSave": "afterDelay",
        "atlascode.jira.lastCreateSiteAndProject": {},
        "workbench.activityBar.visible": false,
        "blade.format.enable": true,
        "explorer.confirmDragAndDrop": false,
        "explorer.confirmDelete": false,
        "workbench.statusBar.visible": false,
        "workbench.editor.showTabs": false,
        "workbench.colorCustomizations": {
            "activityBarBadge.background": "#616161",
            "activityBar.activeBorder": "#616161",
            "list.activeSelectionForeground": "#616161",
            "list.inactiveSelectionForeground": "#616161",
            "list.highlightForeground": "#616161",
            "scrollbarSlider.activeBackground": "#61616150",
            "editorSuggestWidget.highlightForeground": "#616161",
            "textLink.foreground": "#616161",
            "progressBar.background": "#616161",
            "pickerGroup.foreground": "#616161",
            "tab.activeBorder": "#616161",
            "notificationLink.foreground": "#616161",
            "editorWidget.resizeBorder": "#616161",
            "editorWidget.border": "#616161",
            "settings.modifiedItemIndicator": "#616161",
            "settings.headerForeground": "#616161",
            "panelTitle.activeBorder": "#616161",
            "breadcrumb.activeSelectionForeground": "#616161",
            "menu.selectionForeground": "#616161",
            "menubar.selectionForeground": "#616161",
            "editor.findMatchBorder": "#616161",
            "selection.background": "#61616140"
        },
        "materialTheme.accent": "Graphite",
        "workbench.sideBar.location": "right",
        "editor.minimap.enabled": false,
        "breadcrumbs.enabled": true,
        "editor.renderWhitespace": "none",
        "timeline.excludeSources": [],
        "php-cs-fixer.executablePath": "${extensionPath}/php-cs-fixer.phar",
        "window.openFilesInNewWindow": "on",
        "diffEditor.renderSideBySide": true,
        "better-phpunit.commandSuffix": "",
        "better-phpunit.suiteSuffix": "",
        "workbench.editor.enablePreview": false,
        "php-cs-fixer.autoFixBySemicolon": true,
        "php-cs-fixer.formatHtml": true,
        "php-cs-fixer.rules": "@PSR2",
        "php-cs-fixer.lastDownload": 1592114458723,
        "window.menuBarVisibility": "toggle",
        "customizeUI.activityBar": "regular",
        "window.title": "${dirty}${activeEditorShort}${separator}${rootName}${separator}",
        "color-highlight.markerType": "dot-before",
        "editor.fontFamily": "'Fira Code', 'Droid Sans Mono', 'monospace', monospace, 'Droid Sans Fallback'",
        "editor.fontLigatures": true,
        "editor.gotoLocation.multipleDefinitions": "goto",
        "cSpell.userWords": [],
        "editor.suggestSelection": "first",
        "vsintellicode.modify.editor.suggestSelection": "automaticallyOverrodeDefaultValue",
        "java.semanticHighlighting.enabled": true,
        "files.exclude": {
            "**/.classpath": true,
            "**/.project": true,
            "**/.settings": true,
            "**/.factorypath": true
        },
        "java.requirements.JDK11Warning": false,
        "[java]": {
            "editor.defaultFormatter": "redhat.vscode-quarkus"
        },
        "gitlens.gitCommands.skipConfirmations": [
            "fetch:command",
            "stash-push:command",
            "switch:command",
            "push:command"
        ],
        "gitlens.views.repositories.files.layout": "tree",
    }

```    