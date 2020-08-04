# Angular Extension Pack

This extension pack packages some of the most popular (and some of my favorite) Angular extensions. If you like it, please leave your `Rating & Review` and share with your friends. If you know any extension that is good for Angular development, just let me know by [creating an issue](https://github.com/doggy8088/angular-extension-pack/issues).

## Extensions Included

### Angular Code Snippets

* [Angular Snippets (Version 8)](https://marketplace.visualstudio.com/items?itemName=johnpapa.Angular2)

  * Let's highlight some of my favorite code snippets that works very well with Angular CLI:
    * HTML Snippets
      * `a-class`: `[class]` binding
      * `a-style`: `[style]` binding
      * `a-ngClass`: `ngClass`
      * `a-ngStyle`: `ngStyle`
      * `a-ngSwitch`: `ngSwitch`
      * `a-select`: `<select>` control
      * `a-ngFor`: `*ngFor`
      * `a-ngForAsync`: `*ngFor` with async
      * `a-ngFor-trackBy`: `*ngFor` with trackBy
      * `a-ngIf`: `*ngIf`
      * `a-ngIfElse`: `*ngIf` with `else`
      * `a-ngModel`: `ngModel`
      * `a-formControlName`: `formControlName`
      * `a-formGroup`: `formGroup`
      * `a-formGroupName`: `formGroupName`
      * `a-routerLink`: `routerLink` (include routerLinkActive)
      * `a-routerLink-param`: `routerLink` with a route parameter (include routerLinkActive)
      * `a-prej`: show the JSON form of a model
      * `a-preja`: show the JSON form of a model, using async
    * TypeScript snippets
      * RxJS
        * `a-rxjs-import`: import RxJs features (e.g. Observable, of, Subject)
        * `a-rxjs-operator`: import RxJs opertors (e.g. map, tap, catchError)
        * `a-pipe`: pipe
      * HttpClient
        * `a-httpclient-get`: `httpClient.get` with Rx Observable
        * `a-http-interceptor`: Empty Angular `HttpInterceptor` for `HttpClient`
        * `a-http-interceptor-headers`: Angular `HttpInterceptor` that sets headers for `HttpClient`
        * `a-http-interceptor-logging`: Angular `HttpInterceptor` that logs traffic for `HttpClient`
        * `a-service-httpclient`: service with `HttpClient`
      * Routes
        * `a-route-path-404`: 404 route path
        * `a-route-path-lazy`: lazy route path
        * `a-route-path-default`: default route path
        * `a-route-path-with-children`: route path with children
        * `a-route-path-eager`: eager route path
        * `a-route-path-lazy`: lazy route path
        * `a-router-events`: listen to one or more router events
        * `a-route-params-subscribe`: subscribe to route parameters
      * Route Guards
        * `a-guard-can-load`: `CanLoad` guard
        * `a-guard-can-activate`: `CanActivate` guard
        * `a-guard-can-activate-child`: `CanActivateChild` guard
        * `a-guard-can-deactivate`: `CanDeactivate` guard
      * Misc
        * `a-preload-strategy`: implements PreloadingStrategy class
        * `a-output-event`: `@Output` event and emitter
    * JavaScript snippets
      * `ex-simple-server`: Node.js Express Server
    * Dockerfile snippets
      * `docker-angular-node-multi-stage`: Multi-stage Dockerfile for Node with Angular

* [Angular 8 Snippets - TypeScript, Html, Angular Material, ngRx, RxJS & Flex Layout](https://marketplace.visualstudio.com/items?itemName=Mikael.Angular-BeastCode)

  * Setting: `"editor.snippetSuggestions": "top"`
    * Let default/user/extension snippets are on top of your suggestion list.
  * Snippet Prefixes
    * `t-`    (Test Snippets)
    * `e-`    (Test Expect Snippets)
    * `ng-`   (Angular Snippets)
    * `fx-`   (Angular Flex Layout Snippets)
    * `m-`    (Angular Material Design Snippets)
    * `rx-`   (RxJS Snippets for both TypeScript and JavaScript)
    * `sw-`   (Service Workers Snippets)
    * `pwa-`  (Progressive Web Applications Snippets)
    * `ngrx-` (Angular NgRx Snippets)
    * `ngxs-` (Angular NGXS Snippets)

* Some notes about importing RxJS stuff

  * Try [RxJS Explorer](http://reactive.how/rxjs/explorer) to learn more!
  * In RxJS 6+, there are only 2 kinds of pattern to import things.
    * `import { Observable } from 'rxjs';`
      * import everything that is a **Type**, **Creation methods**, **Scheduler**, **Helper** from `rxjs`!
    * `import { map } from 'rxjs/operators';`
      * all of the **operators** get imported from `rxjs/operators`!

### TypeScript Productivity

* [Auto Import](https://marketplace.visualstudio.com/items?itemName=steoates.autoimport)
* [JavaScript (ES6) code snippets](https://marketplace.visualstudio.com/items?itemName=xabikos.JavaScriptSnippets)
  * Import and export
    * `imp→` imports entire module `import fs from 'fs';`
    * `imn→` imports entire module without module name `import 'animate.css'`
    * `ime→` imports everything as alias from the module `import * as localAlias from 'fs';`
    * `imd→` imports only a portion of the module using destructing `import { rename } from 'fs';`
    * `ima→` imports only a portion of the module as alias `import { rename as localRename } from 'fs';`
    * `enf→` exports name function `export const log = (parameter) => { console.log(parameter);};`
    * `edf→` exports default function `export default (parameter) => { console.log(parameter);};`
    * `ecl→` exports default class `export default class Calculator { };`
    * `ece→` exports default class by extending a base one `export default class Calculator extends BaseClass { };`
  * Class helpers
    * `con→` adds default constructor in the class `constructor() {}`
    * `met→` creates a method inside a class `add() {}`
    * `pge→` creates a getter property `get propertyName() {return value;}`
    * `pse→` creates a setter property `set propertyName(value) {}`
  * Various methods
    * `fre→` forEach loop in ES6 syntax `array.forEach(currentItem => {})`
    * `fof→` for ... of loop `for(let item of object) {}`
    * `fin→` for ... in loop `for(let item in object) {}`
    * `anfn→` creates an anonymous function `(params) => {}`
    * `nfn→` creates a named function `const add = (params) => {}`
    * `sti→` set interval helper method `setInterval(() => {});`
    * `sto→` set timeout helper method `setTimeout(() => {});`
    * `prom→` creates a new Promise `return new Promise((resolve, reject) => {});`
    * `thenCatch→` adds then and catch declaration to a promise `.then((res) => {).catch((err) => {});`
  * Console methods
    * `clg→` console log `console.log(object)`
    * `cdi→` console dir `console.dir`
    * `clt→` console table `console.table`
* [refactorix](https://marketplace.visualstudio.com/items?itemName=krizzdewizz.refactorix)
  * Some of the **Toggle access modifier** are awesome:
    * `x: Add semicolons` ( There is so convenient shortcut: `Ctrl+;` )
    * `x: Remove semicolons` ( There is so convenient shortcut: `Ctrl+Shift+;` )
    * `x: Property to getter/setter`
    * `x: Arrow function all single statement blocks to expression`
* [JSON to TS](https://marketplace.visualstudio.com/items?itemName=MariusAlchimavicius.json-to-ts)
  * Remember to hit `Ctrl+Alt+V` to convert JSON from **clipboard**.
  * Remember to hit `Ctrl+Alt+S` to convert JSON from **selection**.
* [Paste JSON as Code](https://marketplace.visualstudio.com/items?itemName=quicktype.quicktype)
  * `quicktype` infers types from sample JSON data, then outputs strongly typed models and serializers for working with that data in your desired programming language. For more explanation, read [A first look at quicktype](http://blog.quicktype.io/first-look/).
  * It supports `C#`, `Go`, `C++`, `Java`, `TypeScript`, `Swift`, `Elm`, and `JSON Schema`.  I have to say THIS IS AWESOME! Just try it.
  * For simple JSON document, I still using [JSON to TS](https://marketplace.visualstudio.com/items?itemName=MariusAlchimavicius.json-to-ts).  If the JSON document are more complex, [Paste JSON as Code](https://marketplace.visualstudio.com/items?itemName=quicktype.quicktype) is the best choice.
* [Document This](https://marketplace.visualstudio.com/items?itemName=joelday.docthis)
  * Remember to hit `Ctrl+Alt+D` and again `Ctrl+Alt+D` (hit twice) to generates documentation.
* [Latest TypeScript and Javascript Grammar](https://marketplace.visualstudio.com/items?itemName=ms-vscode.typescript-javascript-grammar)
* [Move TS - Move TypeScript files and update relative imports](https://marketplace.visualstudio.com/items?itemName=stringham.move-ts)

### Template Productivity

* [Angular Language Service](https://marketplace.visualstudio.com/items?itemName=Angular.ng-template)
  * This a MUST extension for your Angular development.
  * It provides a rich editing experience for Angular templates such as IntelliSense (Completions lists), Quick info, Go to definition ( `F12` ) and AOT Diagnostic messages.
* [Auto Rename Tag](https://marketplace.visualstudio.com/items?itemName=formulahendry.auto-rename-tag)
  * This might break something in the JS/TS file. So I prefer to turn on **html** and **xml** only.

    ```json
    "auto-rename-tag.activationOnLanguage": [
      "html",
      "xml"
    ],
    ```

* [CSS Peek](https://marketplace.visualstudio.com/items?itemName=pranaygp.vscode-css-peek)
  * Remember to hit `F12` that **Go To** css file and open in a new editor.
  * Remember to hit `Ctrl` to show the definition when hovering over the symbol.

### Code Analysis

* [TSLint](https://marketplace.visualstudio.com/items?itemName=ms-vscode.vscode-typescript-tslint-plugin)
  * This extension works using VS Code's built-in version of TypeScript and a local or global install of tslint. You do not need to configure the plugin in your `tsconfig.json` if you are using VS Code's version of TypeScript.
  * If you are [using a workspace version of typescript](https://code.visualstudio.com/docs/typescript/typescript-compiling#_using-the-workspace-version-of-typescript), you must currently configure the TS Server plugin manually by following [these instructions](https://github.com/Microsoft/typescript-tslint-plugin#configuration-options)
* [Gremlins tracker for Visual Studio Code](https://marketplace.visualstudio.com/items?itemName=nhoizey.gremlins)
  * Reveals some characters that can be harmful because they are invisible or looking like legitimate ones. It could possibly cost you few hours to find out problems.

### Code Navigation

* [angular2-switcher](https://marketplace.visualstudio.com/items?itemName=infinity1207.angular2-switcher)
  * Remember to use `Alt+o` shortcut to switch between Component and the HTML Template.

### Collaboration

* [EditorConfig for VS Code](https://marketplace.visualstudio.com/items?itemName=EditorConfig.EditorConfig)
  * There is a **EditorConfig: Generate** can generate `.editorconfig` on the fly.

### Workbench

* [VSCode simpler Icons with Angular](https://marketplace.visualstudio.com/items?itemName=davidbabel.vscode-simpler-icons)
  * You have to enable this **File Icon Theme** manually.
    * Windows: **File** → **Preferences** → **File Icon Theme** → **VSCode Great Icons**
    * OSX: **Code** → **Preferences** → **File Icon Theme** → **VSCode Great Icons**
* [TODO Highlight](https://marketplace.visualstudio.com/items?itemName=wayou.vscode-todo-highlight)
  * The TODO Highlight **Keywords** can be customized, see the [docs](https://marketplace.visualstudio.com/items?itemName=wayou.vscode-todo-highlight) for the details.
  * There are two main commands:
    1. **Toggle highlight** : turn on/off the highlight
    2. **List hilighted annotations** : list annotations and reveal from corresponding file
* [Git History](https://marketplace.visualstudio.com/items?itemName=donjayamanne.githistory)
  * This helps you view and search git log along with the graph and details. Awesome!
  * It also support **Compare**, **Cherry pick**, **Revert**, **Create branches from a commits** actions.
* [Angular Schematics](https://marketplace.visualstudio.com/items?itemName=cyrilletuzi.angular-schematics)
  * Allows you to launch Angular schematics (CLI commands) from files Explorer (right-click) or Command Palette.

### Some other extensions you may need (Optional) (You need to install the following extensions manually.)

* [Peacock](https://marketplace.visualstudio.com/items?itemName=johnpapa.vscode-peacock)
  * Subtly change the workspace color of your workspace. Ideal when you have multiple VS Code instances and you want to quickly identify which is which.
* [Angular Console](https://marketplace.visualstudio.com/items?itemName=nrwl.angular-console)
  * The user interface app for the Angular CLI.
* [Prettier - JavaScript formatter](https://marketplace.visualstudio.com/items?itemName=esbenp.prettier-vscode)
  * Setting: `"prettier.singleQuote": true`
    * We love single quote on strings. Isn't it?
  * Setting: `"editor.formatOnSave": false`
    * Prettier use AST to parse your source code so you can safely enable `editor.formatOnSave` setting.
  * Recommended reading: [Setting up Prettier in an Angular CLI Project](https://medium.com/@victormejia/setting-up-prettier-in-an-angular-cli-project-2f50c3b9a537)
* [AngularDoc for Visual Studio Code](https://marketplace.visualstudio.com/items?itemName=AngularDoc.angulardoc-vscode)
  * Sometimes it's buggy. Many of our projects are unable to produce documentation.
* [Git Lens — git blame annotations, code lens, and more](https://marketplace.visualstudio.com/items?itemName=eamodio.gitlens)
  * It's too informative for me. I turn it off all the time.
* [Bracket Pair Colorizer](https://marketplace.visualstudio.com/items?itemName=CoenraadS.bracket-pair-colorizer)
  * I don't need this extension usually, but maybe someone needs it.
* [angular2-inline](https://marketplace.visualstudio.com/items?itemName=natewallace.angular2-inline)
  * I don't use **inline template** at all. If you need it, you can install this extension. I don't like to mix HTML with TypeScript anyway.
* [Angular Component Extension](https://marketplace.visualstudio.com/items?itemName=onixie.angular-component-extension)
  * Language support for **inline-defined template** and styles.
  * I don't use **inline template** at all. If you need it, you can install this extension.
* [TypeScript Importer](https://marketplace.visualstudio.com/items?itemName=pmneo.tsimporter)
  * Setting: `"tsimporter.noStatusBar": true`
* [TypeScript Toolbox](https://marketplace.visualstudio.com/items?itemName=DSKWRK.vscode-generate-getter-setter)
  * Setting: `"genGetSet.spacedImportLine": true`
  * Some features are broken.
* [Output Colorizer](https://marketplace.visualstudio.com/items?itemName=IBM.output-colorizer)
  * This colorize your messages in the **Output**/**Debug**/**Extensions** panel and all the `*.log` files.
* [Wallaby.js](https://marketplace.visualstudio.com/items?itemName=WallabyJs.wallaby-vscode)
  * Integrated Continuous Testing Tool for JavaScript.
* [Quokka.js](https://marketplace.visualstudio.com/items?itemName=WallabyJs.quokka-vscode)
  * Live Scratchpad for JavaScript.
* [Todo Tree](https://marketplace.visualstudio.com/items?itemName=Gruntfuggly.todo-tree)
  * TODO Tree just did an amazing job for highlighting the TODO's in the source code.
  * It can aggregate all the TODO's in the project into sidebar.
  * All the colors can be customized. New comment tags can be customized as well.

### Other manual setup (Optional)

* Recommended Editor Fonts Settings
  * English
    * `"editor.fontFamily": "Fira Code, Consolas, 'Courier New', monospace"`
      * Install [FiraCode: Monospaced font with programming ligatures](https://github.com/tonsky/FiraCode)
      * The [FiraCode](https://github.com/tonsky/FiraCode) provided a ligatures feature for your code which is pretty cool. You have to set `"editor.fontLigatures": true` to enabled it.
  * 繁體中文
    * `"editor.fontLigatures": true`
    * `"editor.fontFamily": "Fira Code, 'Noto Sans CJK TC Medium', Consolas, 'Courier New', monospace"`
    * Install [Google Noto Fonts - Noto Sans CJK TC](https://www.google.com/get/noto/#sans-hant)
    * Install [FiraCode: Monospaced font with programming ligatures](https://github.com/tonsky/FiraCode)
  * 简体中文
    * `"editor.fontLigatures": true`
    * `"editor.fontFamily": "Fira Code, 'Noto Sans CJK SC Medium', Consolas, 'Courier New', monospace"`
    * Install [Google Noto Fonts - Noto Sans CJK SC](https://www.google.com/get/noto/#sans-hans)
    * Install [FiraCode: Monospaced font with programming ligatures](https://github.com/tonsky/FiraCode)
* Recommended Settings
  * `"editor.minimap.renderCharacters": false`
    * Enhanced minimap performance by disabling render characters in minimap.
  * `"emmet.showSuggestionsAsSnippets": true`
    * Treat all emmet suggestion as snippets can make all suggestions get sorted alphabetically.

## Snippets Included

This extension contains supplementary code snippets to [Angular v7 Snippets](https://marketplace.visualstudio.com/items?itemName=johnpapa.Angular2) & [Angular 7 Snippets - TypeScript, Html, Angular Material, ngRx, RxJS & Flex Layout](https://marketplace.visualstudio.com/items?itemName=Mikael.Angular-BeastCode).

### TypeScript snippets

* `ng-import-FormsModule`: imports `FormsModule` from `@angular/forms`
* `ng-import-ReactiveFormsModule`: imports `ReactiveFormsModule` from `@angular/forms`
* `ng-import-HttpClientModule`: imports `HttpClientModule` from `@angular/common/http`
* `ng-import-HttpClient`: imports `HttpClient` from `@angular/common/http`
* `ng-import-createCustomElement`: imports `createCustomElement` from `@angular/elements`
* `ng-ctor-elements`: create required Angular Elements boilerplate on AppModule's constructor
* `ngDoBootstrap`: generates `ngDoBootstrap()` method for `AppModule`

### HTML snippets

* `a-ngSubmit`: Angular Forms's `ngSubmit` event
* `a-formArrayName`: Angular `formArrayName`
* `a-formGroupName`: Angular `formGroupName`
* `a-routerLinkActive`: Angular `routerLinkActive="active"`
* `a-routerLinkActiveOptions`: Angular `[routerLinkActiveOptions]="{exact: true}"`

**Enjoy!**
