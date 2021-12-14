# Angular Extension Pack

This extension pack packages some of the most popular (and some of my favorite) Angular extensions. If you like it, please leave your `Rating & Review` and share with your friends. If you know any extension that is good for Angular development, just let me know by [creating an issue](https://github.com/doggy8088/angular-extension-pack/issues).

## Extensions Included

### Angular-specific Tools

* [Angular Language Service](https://marketplace.visualstudio.com/items?itemName=Angular.ng-template)
  * This a MUST extension for your Angular development.
  * It provides a rich editing experience for Angular templates such as IntelliSense (Completions lists), Quick info, Go to definition ( `F12` ) and AOT Diagnostic messages.
* [Angular Schematics](https://marketplace.visualstudio.com/items?itemName=cyrilletuzi.angular-schematics)
  * Allows you to launch Angular schematics (CLI commands) from files Explorer (right-click) or Command Palette.
* [angular2-switcher](https://marketplace.visualstudio.com/items?itemName=infinity1207.angular2-switcher)
  * Remember to use `Alt+o` shortcut to switch between Component and the HTML Template.

### Angular Code Snippets

* [Angular Snippets (Version 12)](https://marketplace.visualstudio.com/items?itemName=johnpapa.Angular2)

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

* [Angular 10 Snippets - TypeScript, Html, Angular Material, ngRx, RxJS & Flex Layout](https://marketplace.visualstudio.com/items?itemName=Mikael.Angular-BeastCode)

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
* [Paste JSON as Code (Refresh)](https://marketplace.visualstudio.com/items?itemName=doggy8088.quicktype-refresh)
  * `quicktype` infers types from sample JSON data, then outputs strongly typed models and serializers for working with that data in your desired programming language. For more explanation, read [A first look at quicktype](http://blog.quicktype.io/first-look/).
  * It supports `C#`, `Go`, `C++`, `Java`, `TypeScript`, `Swift`, `Elm`, and `JSON Schema`.  I have to say THIS IS AWESOME! Just try it.
* [Document This](https://marketplace.visualstudio.com/items?itemName=oouo-diogo-perdigao.docthis)
  * Remember to hit `Ctrl+Alt+D` and again `Ctrl+Alt+D` (hit twice) to generates documentation.
* [Move TS - Move TypeScript files and update relative imports](https://marketplace.visualstudio.com/items?itemName=stringham.move-ts)

### Template Productivity

* Enable VSCode built-in **Linked Editing** ([Auto update tags](https://code.visualstudio.com/Docs/languages/html#_auto-update-tags)) feature.

    ```json
    "editor.linkedEditing": true
    ```

* [CSS Peek](https://marketplace.visualstudio.com/items?itemName=pranaygp.vscode-css-peek)
  * Remember to hit `F12` on the CSS class in HTML that will trigger **Go To Definition** command and preview CSS content.

### Code Analysis

* [ESLint](https://marketplace.visualstudio.com/items?itemName=dbaeumer.vscode-eslint)
  * TSLint's support for Angular CLI is discontinued and it already marking deprecated since Angular CLI 11.
  * You can follow [this guideline](https://github.com/angular-eslint/angular-eslint#migrating-an-angular-cli-project-from-codelyzer-and-tslint) for migrating an Angular CLI project from Codelyzer and TSLint to ESLint.
* [Gremlins tracker for Visual Studio Code](https://marketplace.visualstudio.com/items?itemName=nhoizey.gremlins)
  * Reveals some characters that can be harmful because they are invisible or looking like legitimate ones. It could possibly cost you few hours to find out problems.

### Workbench

* [EditorConfig for VS Code](https://marketplace.visualstudio.com/items?itemName=EditorConfig.EditorConfig)
  * You can right-click on any folder in the **EXPLORER** pane and choose **Generate .editorconfig** command.
* [VSCode simpler Icons with Angular](https://marketplace.visualstudio.com/items?itemName=davidbabel.vscode-simpler-icons)
  * You have to enable this **File Icon Theme** manually.
    * Windows: **File** → **Preferences** → **File Icon Theme** → **VSCode Great Icons**
    * OSX: **Code** → **Preferences** → **File Icon Theme** → **VSCode Great Icons**
* [Todo Tree](https://marketplace.visualstudio.com/items?itemName=Gruntfuggly.todo-tree)
  * TODO Tree just did an amazing job for highlighting the TODO's in the source code.
  * It can aggregate all the TODO's in the project into sidebar.
  * All the colors can be customized. New comment tags can be customized as well.
* [Git Graph](https://marketplace.visualstudio.com/items?itemName=mhutchie.git-graph)
  * The best `git log` extension for Visual Studio Code!

### Some other extensions you may need (Optional)

> You need to install the following extensions manually.

* [JavaScript Debugger](https://marketplace.visualstudio.com/items?itemName=ms-vscode.js-debug)
  * An extension for debugging Node.js programs and Chrome.
* [Nx Console](https://marketplace.visualstudio.com/items?itemName=nrwl.angular-console)
  * The user interface app for the Angular CLI.
* [Prettier - JavaScript formatter](https://marketplace.visualstudio.com/items?itemName=esbenp.prettier-vscode)
  * Setting: `"prettier.singleQuote": true`
    * We love single quote on strings. Isn't it?
  * Setting: `"editor.formatOnSave": false`
    * Prettier use AST to parse your source code so you can safely enable `editor.formatOnSave` setting.
  * Recommended reading: [Setting up Prettier in an Angular CLI Project](https://medium.com/@victormejia/setting-up-prettier-in-an-angular-cli-project-2f50c3b9a537)
* [Git Extension Pack](https://marketplace.visualstudio.com/items?itemName=doggy8088.git-extension-pack)
  * Popular Visual Studio Code extensions for Git version control
    * [GitLens — Git supercharged](https://marketplace.visualstudio.com/items?itemName=eamodio.gitlens)
      * Setting: `"gitlens.currentLine.enabled": false`
    * [Git Graph](https://marketplace.visualstudio.com/items?itemName=mhutchie.git-graph)
    * [gitignore](https://marketplace.visualstudio.com/items?itemName=codezombiech.gitignore)
    * [Open in GitHub, Bitbucket, Gitlab, VisualStudio.com !](https://marketplace.visualstudio.com/items?itemName=ziyasal.vscode-open-in-github)
    * [GitHub Repositories](https://marketplace.visualstudio.com/items?itemName=GitHub.remotehub)
* [Live Share](https://marketplace.visualstudio.com/items?itemName=MS-vsliveshare.vsliveshare)
  * Real-time collaborative development from the comfort of your favorite tools.
* [Peacock](https://marketplace.visualstudio.com/items?itemName=johnpapa.vscode-peacock)
  * Subtly change the workspace color of your workspace. Ideal when you have multiple VS Code instances and you want to quickly identify which is which.
* [Bracket Pair Colorizer](https://marketplace.visualstudio.com/items?itemName=CoenraadS.bracket-pair-colorizer)
  * I don't need this extension usually, but maybe someone needs it.
* [Output Colorizer](https://marketplace.visualstudio.com/items?itemName=IBM.output-colorizer)
  * This colorize your messages in the **Output**/**Debug**/**Extensions** panel and all the `*.log` files.
* [Wallaby.js](https://marketplace.visualstudio.com/items?itemName=WallabyJs.wallaby-vscode)
  * Integrated Continuous Testing Tool for JavaScript.
* [Quokka.js](https://marketplace.visualstudio.com/items?itemName=WallabyJs.quokka-vscode)
  * Live Scratchpad for JavaScript.
* [AngularDoc for Visual Studio Code](https://marketplace.visualstudio.com/items?itemName=AngularDoc.angulardoc-vscode)
  * Sometimes it's buggy. Many of our projects are unable to produce documentation.
* [arrr](https://marketplace.visualstudio.com/items?itemName=obenjiro.arrr)
  * Sometimes it's buggy. The extension provides refactoring tools for your Angular codebase.
* [angular2-inline](https://marketplace.visualstudio.com/items?itemName=natewallace.angular2-inline)
  * I don't use **inline template** at all. If you need it, you can install this extension. I don't like to mix HTML with TypeScript anyway.

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

This extension contains supplementary code snippets to [Angular Snippets (Version 12)](https://marketplace.visualstudio.com/items?itemName=johnpapa.Angular2) & [Angular 10 Snippets - TypeScript, Html, Angular Material, ngRx, RxJS & Flex Layout](https://marketplace.visualstudio.com/items?itemName=Mikael.Angular-BeastCode).

### TypeScript snippets

* app.module.ts (Angular Module)
  * `ng-import-FormsModule`: imports `FormsModule` from `@angular/forms`
  * `ng-import-ReactiveFormsModule`: imports `ReactiveFormsModule` from `@angular/forms`
  * `ng-import-HttpClientModule`: imports `HttpClientModule` from `@angular/common/http`
  * `ngDoBootstrap`: generates `ngDoBootstrap()` method for `AppModule`
* app.module.ts (Angular Elements)
  * `ng-import-element`: imports `createCustomElement` and `Injector` for Angular Elements
  * `ng-elements`: create required Angular Elements boilerplate on AppModule
  * `ng-import-LazyElementsModule`: imports `LazyElementsModule` from `@angular-extensions/elements`
* main.ts
  * `ng-bootstrapModule-NoopZone`: Setting up [NoopZone](https://angular.io/guide/zone#noopzone) in `main.ts`
* polyfills.ts
  * `ng-polyfills-zonejs-flags`: Setting up [Zone.js](https://angular.io/guide/zone) flags

### HTML snippets

* `a-ngSubmit`: Angular Forms's `ngSubmit` event
* `a-formArrayName`: Angular `formArrayName`
* `a-formGroupName`: Angular `formGroupName`
* `a-routerLinkActive`: Angular `routerLinkActive="active"`
* `a-routerLinkActiveOptions`: Angular `[routerLinkActiveOptions]="{exact: true}"`
* `a-axLazyElement`: Lazy load **Angular Elements** or **any other web components** / **custom elements**

### NGINX snippets

* `ng-nginx`: NGINX configuration for Angular (`nginx.conf`)

### Dockerfile snippets

* `ng-dockerfile`: Multi-stage build for Angular and Nginx Dockerfile
  * In this snippet, you can choose between `ng build` or `npm run build --` command.

**Enjoy!**
