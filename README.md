# Angular Extension Pack

This extension pack pakcages some of the most popular (and some of my favorite) Angular  extensions.  If you like it, please leave your `Rating & Review` and share with your friends.  If you know any extension that is good for Angular development, just let me know by [creating an issue](https://github.com/doggy8088/angular-extension-pack/issues).

## Extensions Included

### Angular Code Snippets

- [Angular v4 TypeScript Snippets](https://marketplace.visualstudio.com/items?itemName=johnpapa.Angular2)
    - Let's highlight some of my favorite code snippets that works very well with Angular CLI:
        - `a-guard-can-deactivate`: Angular CLI can only generate `CanActivate` guard by default.
        - `a-output-event`: generate an `@Output` event and emitter
        - `a-route-path-lazy`: generate an lazy route path
        - `a-service-http`: service with `Http`
        - `a-service-httpclient`: service with `HttpClient`
        - `rx-observable`: Rx Observable import
        - `rx-add-operator`: Rx add observable import
        - `rx-add-operator`: Rx add operator import
        - `a-select`: `<select>` control
        - `a-ngIf`: `*ngIf`
        - `a-ngFor`: `*ngFor`
        - `a-ngForAsync`: `*ngFor` with async
        - `a-ngModel`: `ngModel`
        - `a-routerLink`: `routerLink`
- [Angular 2+ Snippets - TypeScript, Html, ngRx, Angular Flex Layout & Testing](https://marketplace.visualstudio.com/items?itemName=Mikael.Angular-BeastCode)
    - Setting: `"editor.snippetSuggestions": "top"`
        - Let default/user/extension snippets are on top of your suggestion list.

### TypeScript Productivity

- [Path Intellisense](https://marketplace.visualstudio.com/items?itemName=christian-kohler.path-intellisense)
- [TypeScript Importer](https://marketplace.visualstudio.com/items?itemName=pmneo.tsimporter)
    - Setting: `"tsimporter.noStatusBar": true`
- [TypeScript Toolbox](https://marketplace.visualstudio.com/items?itemName=DSKWRK.vscode-generate-getter-setter)
    - Setting: `"genGetSet.spacedImportLine": true`
- [JavaScript (ES6) code snippets](https://marketplace.visualstudio.com/items?itemName=xabikos.JavaScriptSnippets)
    - Some of the code snippets are very useful and used very often:
        - `imd→` imports only a portion of the module using destructing  `import {rename} from 'fs';`
        - `con→` adds default constructor in the class `constructor() {}`
        - `fof→` for ... of loop `for(let item of object) {}`
        - `fin→` for ... in loop `for(let item in object) {}`
        - `sti→` set interval helper method `setInterval(() => {});`
        - `sto→` set timeout helper method `setTimeout(() => {});`
        - `clg→` console log `console.log(object)`
        - `cdi→` console dir `console.dir`
- [refactorix](https://marketplace.visualstudio.com/items?itemName=krizzdewizz.refactorix)
    - Some of the **Toggle access modifier** are awesome:
        - `x: Add semicolons` ( There is so convenient shortcut: `Ctrl+;` )
        - `x: Remove semicolons` ( There is so convenient shortcut: `Ctrl+Shift+;` )
        - `x: Property to getter/setter`
        - `x: Arrow function all single statement blocks to expression`
- [Beautify](https://marketplace.visualstudio.com/items?itemName=HookyQR.beautify)
    - Setting: `"html.format.wrapLineLength": 0` (I don't like HTML been wrapped automatically.)
    - Setting: `"html.format.wrapAttributes": "auto"` ( or `"force-expand-multiline"` )
    - Setting: I removed `label` and `button` tag from `html.format.unformatted`.  It because there is a common skill that `label` can wrap `input` and text sometimes.  Also, the `button` tag are usually put image, Glyphicons or some other stuff in it especially when using [Bootstrap](https://getbootstrap.com/).
        ```
        "html.format.unformatted": "a, abbr, acronym, b, bdo, big, br, cite, code, dfn, em, i, img, input, kbd, map, object, q, samp, select, small, span, strong, sub, sup, textarea, tt, var"
        ```
    - For more settings, please check [VSCodeBeautify/Settings](https://github.com/HookyQR/VSCodeBeautify/blob/master/Settings.md) docs.
    - See also: [.editorconfig's indent_size doesn't applied on HTML file #170](https://github.com/HookyQR/VSCodeBeautify/issues/170)
- [JSON to TS](https://marketplace.visualstudio.com/items?itemName=MariusAlchimavicius.json-to-ts)
    - Remember to hit `Ctrl+Alt+V` to convert JSON from **clipboard**.
    - Remember to hit `Ctrl+Alt+S` to convert JSON from **selection**.
- [Document This](https://marketplace.visualstudio.com/items?itemName=joelday.docthis)
    - Remember to hit `Ctrl+Alt+D` and again `Ctrl+Alt+D` (hit twice) to generates documentation.
- [Latest TypeScript and Javascript Grammar](https://marketplace.visualstudio.com/items?itemName=ms-vscode.typescript-javascript-grammar)

### Template Productivity

- [Angular Language Service](https://marketplace.visualstudio.com/items?itemName=Angular.ng-template)
    - This a MUST extension for your Angular development.
    - It provide a rich editing experience for Angular templates such as IntelliSense (Completions lists), Quick info, Go to definition ( `F12` ) and AOT Diagnostic messages.
- [Auto Rename Tag](https://marketplace.visualstudio.com/items?itemName=formulahendry.auto-rename-tag)
    - This might broken something in the JS/TS file.  So I prefer to turn on **html** and **xml** only.
        ```
        "auto-rename-tag.activationOnLanguage": [
                "html",
                "xml"
            ],
        ```
- [CSS Peek](https://marketplace.visualstudio.com/items?itemName=pranaygp.vscode-css-peek)
    - Remember to hit `F12` that **Go To** css file and open in a new editor.
    - Remember to hit `Ctrl` to show the definition in a hover over the symbol.

### Code Analysis

- [TSLint](https://marketplace.visualstudio.com/items?itemName=eg2.tslint)
    - Setting: `"tslint.autoFixOnSave": true` ( [See also](https://github.com/Microsoft/TypeScript/issues/13270#issuecomment-292298260) )
    - Setting: `"tslint.enable": false` ( Sometimes you may need some rest for these tslint rules! )

### Code Navigation

- [angular2-switcher](https://marketplace.visualstudio.com/items?itemName=infinity1207.angular2-switcher)
    - Remember to use `Alt+o` shortcut to switch between Component and the HTML Template.

### Collaboration

- [EditorConfig for VS Code](https://marketplace.visualstudio.com/items?itemName=EditorConfig.EditorConfig)
    - There is a **EditorConfig: Generate** can generate `.editorconfig` on the fly.

### Workbench

- [VSCode simpler Icons with Angular](https://marketplace.visualstudio.com/items?itemName=davidbabel.vscode-simpler-icons)
- [Output Colorizer](https://marketplace.visualstudio.com/items?itemName=IBM.output-colorizer)
- [Angular-io-Code](https://marketplace.visualstudio.com/items?itemName=NoHomey.angular-io-code)

### Some other extensions you may need (Optional) (You need to install the following extensions manually.)

- [AngularDoc for Visual Studio Code](https://marketplace.visualstudio.com/items?itemName=AngularDoc.angulardoc-vscode)
    - Sometimes it's buggy.  Many of our projects are unable to produce documentation.
- [Git Lens](https://marketplace.visualstudio.com/items?itemName=eamodio.gitlens)
    - It's too informative for me.  I turn it off all the time.
- [Bracket Pair Colorizer](https://marketplace.visualstudio.com/items?itemName=CoenraadS.bracket-pair-colorizer)
    - I don't need this extension usually, but maybe someone need it. 
- [angular2-inline](https://marketplace.visualstudio.com/items?itemName=natewallace.angular2-inline)
    - I don't use **inline template** at all.  If you need it, you can install this extension.  I don't like mix HTML with TypeScript anyway.

### Other manual setup (Optional)

- Recommended Editor Fonts Settings
    - English
        - `"editor.fontFamily": "Fira Code, Consolas, 'Courier New', monospace"`
            - Install [FiraCode: Monospaced font with programming ligatures](https://github.com/tonsky/FiraCode)
            - The [FiraCode](https://github.com/tonsky/FiraCode) provided a ligatures feature for your code which is pretty cool.  You have to set `"editor.fontLigatures": true` to enabled it.
    - 繁體中文
        - `"editor.fontLigatures": true`
        - `"editor.fontFamily": "Fira Code, 'Noto Sans CJK TC Medium', Consolas, 'Courier New', monospace"`
        - Install [Google Noto Fonts - Noto Sans CJK TC](https://www.google.com/get/noto/#sans-hant)
        - Install [FiraCode: Monospaced font with programming ligatures](https://github.com/tonsky/FiraCode)
    - 简体中文
        - `"editor.fontLigatures": true`
        - `"editor.fontFamily": "Fira Code, 'Noto Sans CJK SC Medium', Consolas, 'Courier New', monospace"`
        - Install [Google Noto Fonts - Noto Sans CJK SC](https://www.google.com/get/noto/#sans-hans)
        - Install [FiraCode: Monospaced font with programming ligatures](https://github.com/tonsky/FiraCode)
- Recommended Settings
    - `"editor.minimap.renderCharacters": false`
        - Enhanced minimap performance by disabling render characters in minimap.
    - `"emmet.showSuggestionsAsSnippets": true`
        - Treat all emmet suggestion as snippets can make all suggestions get sorted alphabetically.

**Enjoy!**