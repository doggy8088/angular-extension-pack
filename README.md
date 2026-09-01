# Angular Extension Pack

This extension pack groups Angular-focused extensions for language support, code generation, snippets, linting, and daily development tasks. The bundled extensions are installed automatically with the pack. If you have suggestions for new extensions or improvements, please [open an issue](https://github.com/doggy8088/angular-extension-pack/issues).

## Extensions Included

### Angular-specific Tools

* [Angular Language Service](https://marketplace.visualstudio.com/items?itemName=Angular.ng-template)
  * Angular template IntelliSense, diagnostics, quick info, and navigation.
* [Angular Schematics](https://marketplace.visualstudio.com/items?itemName=cyrilletuzi.angular-schematics)
  * Run Angular CLI schematics from the Explorer or Command Palette.
* [angular2-switcher](https://marketplace.visualstudio.com/items?itemName=infinity1207.angular2-switcher)
  * Quickly switch between an Angular component and its HTML template.

### Angular Code Snippets

* [Angular Snippets (Version 22)](https://marketplace.visualstudio.com/items?itemName=johnpapa.Angular2)
  * Angular component, template, routing, forms, HTTP, and RxJS snippets.

* [Angular 17 Snippets - TypeScript, Html, Angular Material, ngRx, RxJS & Flex Layout](https://marketplace.visualstudio.com/items?itemName=Mikael.Angular-BeastCode)
  * Snippets for Angular, Angular Material, RxJS, NgRx, tests, and related tooling.
  * Use `"editor.snippetSuggestions": "top"` to prioritize snippet completions.

### TypeScript Productivity

* [Auto Import](https://marketplace.visualstudio.com/items?itemName=steoates.autoimport)
  * Suggests and inserts imports for symbols from project and package dependencies.
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
  * Applies source transformations such as semicolon changes, accessors, and arrow-function simplification.
* [Paste JSON as Code (Refresh)](https://marketplace.visualstudio.com/items?itemName=doggy8088.quicktype-refresh)
  * Generates typed models and serializers from sample JSON data.
* [Document This](https://marketplace.visualstudio.com/items?itemName=oouo-diogo-perdigao.docthis)
  * Generates documentation comments for JavaScript and TypeScript declarations.

### Template Productivity

* Enable VSCode built-in **Linked Editing** ([Auto update tags](https://code.visualstudio.com/Docs/languages/html#_auto-update-tags)) feature.

    ```json
    "editor.linkedEditing": true
    ```

### Code Analysis

* [ESLint](https://marketplace.visualstudio.com/items?itemName=dbaeumer.vscode-eslint)
  * Integrates ESLint diagnostics and fixes into VS Code using the project's ESLint configuration.
* [Gremlins tracker for Visual Studio Code](https://marketplace.visualstudio.com/items?itemName=nhoizey.gremlins)
  * Highlights invisible or visually ambiguous characters that can be difficult to detect in source files.

### Workbench

* [EditorConfig for VS Code](https://marketplace.visualstudio.com/items?itemName=EditorConfig.EditorConfig)
  * Applies `.editorconfig` rules consistently across supported editors and projects.
* [Todo Tree](https://marketplace.visualstudio.com/items?itemName=Gruntfuggly.todo-tree)
  * Finds TODO, FIXME, and other configured tags and displays them in a navigable tree.

### Some other extensions you may need (Optional)

> You need to install the following extensions manually.

* [Prettier - Code formatter](https://marketplace.visualstudio.com/items?itemName=esbenp.prettier-vscode)
  * The code formatting is a subjective preferences. Your choice matters. I choose [Prettier](https://prettier.io/)!
  * Setting: `"prettier.singleQuote": true`
    * We love single quote on strings. Isn't it?
  * Setting: `"editor.formatOnSave": false`
    * Prettier use AST to parse your source code so you can safely enable `editor.formatOnSave` setting.
  * Recommended reading: [Setting up Prettier in an Angular CLI Project](https://medium.com/@victormejia/setting-up-prettier-in-an-angular-cli-project-2f50c3b9a537)
* [Live Share](https://marketplace.visualstudio.com/items?itemName=MS-vsliveshare.vsliveshare)
  * Real-time collaborative development from the comfort of your favorite tools.
* [Peacock](https://marketplace.visualstudio.com/items?itemName=johnpapa.vscode-peacock)
  * Subtly change the workspace color of your workspace. Ideal when you have multiple VS Code instances and you want to quickly identify which is which.
* [Output Colorizer](https://marketplace.visualstudio.com/items?itemName=IBM.output-colorizer)
  * This colorize your messages in the **Output**/**Debug**/**Extensions** panel and all the `*.log` files.
* [angular2-inline](https://marketplace.visualstudio.com/items?itemName=natewallace.angular2-inline)
  * I don't use **inline template** at all. If you need it, you can install this extension. I don't like to mix HTML with TypeScript anyway.
* [Git Extension Pack](https://marketplace.visualstudio.com/items?itemName=doggy8088.git-extension-pack)
  * Popular Visual Studio Code extensions for Git version control
    * [GitLens — Git supercharged](https://marketplace.visualstudio.com/items?itemName=eamodio.gitlens)
      * Setting: `"gitlens.currentLine.enabled": false`
    * [Git Graph](https://marketplace.visualstudio.com/items?itemName=mhutchie.git-graph)
    * [gitignore](https://marketplace.visualstudio.com/items?itemName=codezombiech.gitignore)
    * [Open in GitHub, Bitbucket, Gitlab, VisualStudio.com !](https://marketplace.visualstudio.com/items?itemName=ziyasal.vscode-open-in-github)
    * [GitHub Repositories](https://marketplace.visualstudio.com/items?itemName=GitHub.remotehub)
* [JavaScript Debugger](https://marketplace.visualstudio.com/items?itemName=ms-vscode.js-debug)
  * An extension for debugging Node.js programs and Chrome.
* [Wallaby.js](https://marketplace.visualstudio.com/items?itemName=WallabyJs.wallaby-vscode)
  * Integrated Continuous Testing Tool for JavaScript.
* [Quokka.js](https://marketplace.visualstudio.com/items?itemName=WallabyJs.quokka-vscode)
  * Live Scratchpad for JavaScript.
* [NGINX Configuration Language Support](https://marketplace.visualstudio.com/items?itemName=ahmadalli.vscode-nginx-conf)
  * If you want to use `ng-nginx` snippet, you might want to install this extension for authoring `nginx.conf` file.
* [Material Icon Theme](https://marketplace.visualstudio.com/items?itemName=PKief.material-icon-theme)
* [VSCode simpler Icons with Angular](https://marketplace.visualstudio.com/items?itemName=davidbabel.vscode-simpler-icons)
* [Nx Console](https://marketplace.visualstudio.com/items?itemName=nrwl.angular-console)
  * This let you spend less time looking up command line arguments. Really useful!
* [SCSS Formatter](https://marketplace.visualstudio.com/items?itemName=sibiraj-s.vscode-scss-formatter)
* [SCSS IntelliSense](https://marketplace.visualstudio.com/items?itemName=mrmlnc.vscode-scss)

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

This extension contains supplementary code snippets to [Angular Snippets (Version 22)](https://marketplace.visualstudio.com/items?itemName=johnpapa.Angular2) & [Angular 17 Snippets - TypeScript, Html, Angular Material, ngRx, RxJS & Flex Layout](https://marketplace.visualstudio.com/items?itemName=Mikael.Angular-BeastCode).

### TypeScript snippets

* main.ts (Standalone component)
  * `ng-import-provideHttpClient`: imports `provideHttpClient` from `@angular/common/http`
* app.module.ts (NgModule compatibility)
  * `ng-import-FormsModule`: imports `FormsModule` from `@angular/forms`
  * `ng-import-ReactiveFormsModule`: imports `ReactiveFormsModule` from `@angular/forms`
  * `ng-import-HttpClientModule`: imports `HttpClientModule` from `@angular/common/http`
  * `ngDoBootstrap`: generates `ngDoBootstrap()` method for `AppModule`
* app.module.ts (Angular Elements)
  * `ng-import-elements`: imports `createCustomElement` and `Injector` for Angular Elements
  * `ng-elements`: generates Angular Elements registration boilerplate for an `AppModule`

### HTML snippets

* `a-ngSubmit`: Angular Forms's `ngSubmit` event
* `a-formArrayName`: Angular `formArrayName`
* `a-formGroupName`: Angular `formGroupName`
* `a-routerLinkActive`: Angular `routerLinkActive="active"`
* `a-routerLinkActiveOptions`: Angular `[routerLinkActiveOptions]="{exact: true}"`

### NGINX snippets

* `ng-nginx`: NGINX configuration for Angular (`nginx.conf`)

### Dockerfile snippets

* `ng-dockerfile`: Multi-stage build for Angular and Nginx Dockerfile
  * Review the base images, build output path, and Nginx configuration for your project before use.

**Enjoy!**
