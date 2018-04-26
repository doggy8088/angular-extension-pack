# Angular Extension Pack

This extension pack packages some of the most popular (and some of my favorite) Angular extensions. If you like it, please leave your `Rating & Review` and share with your friends. If you know any extension that is good for Angular development, just let me know by [creating an issue](https://github.com/doggy8088/angular-extension-pack/issues).

## Extensions Included

### Angular Code Snippets

* [Angular v5 Snippets](https://marketplace.visualstudio.com/items?itemName=johnpapa.Angular2)

  * Let's highlight some of my favorite code snippets that works very well with Angular CLI:
    * Template snippets
    * `a-ngIf`: `*ngIf`
    * `a-ngFor`: `*ngFor`
    * `a-ngForAsync`: `*ngFor` with async
    * `a-ngModel`: `ngModel`
    * `a-select`: `<select>` control
    * `a-routerLink`: `routerLink`
    * `a-routerLink-param`: `routerLink` with a route parameter
  * TypeScript snippets
    * `a-route-path-404`: 404 route path
    * `a-route-path-lazy`: lazy route path
    * `rx-observable`: Rx `Observable` import
    * `rx-subject`: Rx `Subject` import
    * `rx-add-operator`: Rx `add` operator import
    * `rx-add-observable`: Rx `add` observable import
    * `rx-operators`: Rx operators import
    * `a-http-get`: `http.get` with Rx Observable
    * `a-httpclient-get`: `httpClient.get` with Rx Observable
    * `a-http-interceptor`: Empty Angular `HttpInterceptor` for `HttpClient`
    * `a-http-interceptor-headers`: Angular `HttpInterceptor` that sets headers for `HttpClient`
    * `a-http-interceptor-logging`: Angular `HttpInterceptor` that logs traffic for `HttpClient`
    * `a-service-http`: service with `Http`
    * `a-service-httpclient`: service with `HttpClient`
    * `a-guard-can-activate`: `CanActivate` guard
    * `a-guard-can-deactivate`: `CanDeactivate` guard
    * `a-output-event`: `@Output` event and emitter

* [Angular 5 Snippets - TypeScript, Html, Angular Material, ngRx, RxJS & Flex Layout](https://marketplace.visualstudio.com/items?itemName=Mikael.Angular-BeastCode)

  * Setting: `"editor.snippetSuggestions": "top"`
    * Let default/user/extension snippets are on top of your suggestion list.
  * Snippet Prefixes
    | Prefix | Description |
    | ------- | ----------- |
    | `ng-` | Angular Snippets |
    | `rx-` | RxJS Snippets for both TypeScript and JavaScript |
    | `fx-` | Angular Flex Layout Snippets |
    | `m-` | Angular Material Design Snippets |
    | `ngrx-` | Angular NgRx Snippets |

* Some notes about importing RxJS stuff

  * Try [RxJS Explorer](http://reactive.how/rxjs/explorer) to learn more!
  * For `rx-` snippets of the [Angular 5 Snippets](https://marketplace.visualstudio.com/items?itemName=Mikael.Angular-BeastCode) extension, it only contains `rx-import-*` at this time.
    * To know this, you can easily distinguish this extension's `rx-*` with [Angular v5 Snippets](https://marketplace.visualstudio.com/items?itemName=johnpapa.Angular2)'s `rx-*` snippets.
  * Comparsion RxJS snippets between these two extensions
    | [Angular v5 Snippets](https://marketplace.visualstudio.com/items?itemName=johnpapa.Angular2) | [Angular 5 Snippets](https://marketplace.visualstudio.com/items?itemName=Mikael.Angular-BeastCode) | RxJS ver. | Snippet Text |
    | --------------------- | -------------------------- | ---------------------- | --------------------------------------------------------- |
    | `rx-observable`       | `rx-import-observable`     | 5.x  | `import { Observable      } from 'rxjs/Observable';`      |
    | `rx-add-observable`   | `rx-import-add-observable` | 5.x  | `import 'rxjs/add/observable/${1:of}';`                   |
    | `rx-add-operator`     | N/A                        | 5.x  | `import 'rxjs/add/operator/${1:map}';`                    |
    | `rx-operators`        | `rx-import-operator`       | 5.5+ | `import { ${1:switchMap}  } from 'rxjs/operators';`       |
    | `rx-subject`          | N/A                        | 5.x  | `import { Subject         } from 'rxjs/Subject';`         |
    | `rx-replay-subject`   | N/A                        | 5.x  | `import { ReplaySubject   } from 'rxjs/ReplaySubject';`   |
    | `rx-behavior-subject` | N/A                        | 5.x  | `import { BehaviorSubject } from 'rxjs/BehaviorSubject';` |
    | N/A                   | `rx-import-all`            | 5.x  | `import Rx from 'rxjs/Rx';`                               |
  * There are [many ways](https://docs.google.com/presentation/d/1_V1hIBY60vs7YqbH7qDSZosAiaPYTRTUlzUUUFfvvoM/edit#slide=id.g24cf5fc38f_0_474) to import RxJS stuff and it's really confusing. (This hopefully could be fixed on RxJS 6. Thanks [@BenLesh](https://twitter.com/BenLesh).)
    * Operators
      * `import { map } from 'rxjs/operators';`
      * `import { map } from 'rxjs/operator';`
      * `import 'rxjs/add/operator/map';`
      * `import { operators: { map } } from 'rxjs/Rx';`
      * `import * as Rx from 'rxjs';`
      * `import * as Rx from 'rxjs/Rx';`
    * Observables
      * `import { Observable } from 'rxjs/Observable;`
      * `import { Observable } from 'rxjs/Rx';`
      * `import { Observable } from 'rxjs';`
    * More ways to import
      * `import { fromEvent } from 'rxjs/observable/fromEvent';`
      * `import 'rxjs/add/observable/fromEvent';`
      * `import { Observable } from 'rxjs'; // adds fromEvent`
      * `import { FromEventObservable } from 'rxjs/observable/FromEventObservable';`
    * Also, imports could get really long
      * `import { Observable } from 'rxjs/Observable';`
      * `import { fromEvent } from 'rxjs/observable/fromEvent';`
      * `import { of } from 'rxjs/observable/of';`
      * `import { map } from 'rxjs/operators/map';`
      * `import { filter } from 'rxjs/operators/filter';`
      * `import { takeUntil } from 'rxjs/operators/takeUntil;`
      * `import { mergeMap } from 'rxjs/operators/mergeMap';`
      * `import { pipe } from 'rxjs/utils/pipe';`
      * `import { async } from 'rxjs/scheduler/async';`
    * In RxJS 5.5 is got a *little* better
      * `import { Observable } from 'rxjs/Observable';`
      * `import { fromEvent } from 'rxjs/observable/fromEvent';`
      * `import { of } from 'rxjs/observable/of';`
      * `import { map, filter, takeUntil, mergeMap } from 'rxjs/operators';`
      * `import { pipe } from 'rxjs/utils/pipe';`
      * `import { async } from 'rxjs/scheduler/async';`

### TypeScript Productivity

* [Path Intellisense](https://marketplace.visualstudio.com/items?itemName=christian-kohler.path-intellisense)
* [JavaScript (ES6) code snippets](https://marketplace.visualstudio.com/items?itemName=xabikos.JavaScriptSnippets)
  * Some of the code snippets are very useful and used very often:
    * `imd→` imports only a portion of the module using destructing `import {rename} from 'fs';`
    * `con→` adds default constructor in the class `constructor() {}`
    * `fof→` for ... of loop `for(let item of object) {}`
    * `fin→` for ... in loop `for(let item in object) {}`
    * `sti→` set interval helper method `setInterval(() => {});`
    * `sto→` set timeout helper method `setTimeout(() => {});`
    * `clg→` console log `console.log(object)`
    * `cdi→` console dir `console.dir`
* [refactorix](https://marketplace.visualstudio.com/items?itemName=krizzdewizz.refactorix)
  * Some of the **Toggle access modifier** are awesome:
    * `x: Add semicolons` ( There is so convenient shortcut: `Ctrl+;` )
    * `x: Remove semicolons` ( There is so convenient shortcut: `Ctrl+Shift+;` )
    * `x: Property to getter/setter`
    * `x: Arrow function all single statement blocks to expression`
* [Beautify](https://marketplace.visualstudio.com/items?itemName=HookyQR.beautify)
  * Setting: `"html.format.wrapLineLength": 0` (I don't like HTML been wrapped automatically.)
  * Setting: `"html.format.wrapAttributes": "auto"` ( or `"force-expand-multiline"` )
  * Setting: I removed `label` and `button` tag from `html.format.unformatted`. It because there is a common skill that `label` can wrap `input` and text sometimes. Also, the `button` tag are usually put image, Glyphicons or some other stuff in it especially when using [Bootstrap](https://getbootstrap.com/).
    ```json
    "html.format.unformatted": "a, abbr, acronym, b, bdo, big, br, cite, code, dfn, em, i, img, input, kbd, map, object, q, samp, select, small, span, strong, sub, sup, textarea, tt, var"
    ```
  * For more settings, please check [VSCodeBeautify/Settings](https://github.com/HookyQR/VSCodeBeautify/blob/master/Settings.md) docs.
  * See also: [.editorconfig's indent_size doesn't applied on HTML file #170](https://github.com/HookyQR/VSCodeBeautify/issues/170)
* [JSON to TS](https://marketplace.visualstudio.com/items?itemName=MariusAlchimavicius.json-to-ts)
  * Remember to hit `Ctrl+Alt+V` to convert JSON from **clipboard**.
  * Remember to hit `Ctrl+Alt+S` to convert JSON from **selection**.
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

* [TSLint](https://marketplace.visualstudio.com/items?itemName=eg2.tslint)
  * Setting: `"tslint.autoFixOnSave": true` ( [See also](https://github.com/Microsoft/TypeScript/issues/13270#issuecomment-292298260) )
  * Setting: `"tslint.enable": false` ( Sometimes you may need some rest for these tslint rules! )

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

### Some other extensions you may need (Optional) (You need to install the following extensions manually.)

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

**Enjoy!**
