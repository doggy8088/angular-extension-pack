# Change Log

All notable changes to the "angular-extension-pack" extension pack will be documented in this file.

## 6.5.3 - 2018-09-17

Add a snippet.

* `a-routerLinkActiveOptions`: Angular `[routerLinkActiveOptions]="{exact: true}"`

## 6.5.1 - 2018-09-14

Add three more HTML snippets.

* `a-ngSubmit`: Angular Forms's `ngSubmit` event
* `a-formArrayName`: Angular `formArrayName`
* `a-formGroupName`: Angular `formGroupName`

## 6.5.0 - 2018-09-14

Add some supplementary code snippets to [Angular v6 Snippets](https://marketplace.visualstudio.com/items?itemName=johnpapa.Angular2) & [Angular 6 Snippets - TypeScript, Html, Angular Material, ngRx, RxJS & Flex Layout](https://marketplace.visualstudio.com/items?itemName=Mikael.Angular-BeastCode).

* `ng-import-FormsModule`: imports `FormsModule` from `@angular/forms`
* `ng-import-ReactiveFormsModule`: imports `ReactiveFormsModule` from `@angular/forms`
* `ng-import-HttpClientModule`: imports `HttpClientModule` from `@angular/common/http`
* `ng-import-HttpClient`: imports `HttpClient` from `@angular/common/http`

## 6.4.0 - 2018-08-17

* Add [Angular Schematics](https://marketplace.visualstudio.com/items?itemName=cyrilletuzi.angular-schematics)
  * Allows you to launch Angular schematics (CLI commands) from files Explorer (right-click) or Command Palette.
* Use `extensionPack` instead of `extensionDependencies` ( VSCode `1.26.0+` )
  * `extensionDependencies` is mainly used to define functional dependencies among extensions that prevents uninstalling or disabling an extension dependency without uninstalling or disabling the dependent extension.

## 6.3.0 - 2018-07-14

* Removed [Beautify](https://marketplace.visualstudio.com/items?itemName=HookyQR.beautify)

## 6.2.0 - 2018-06-12

* Add [Paste JSON as Code](https://marketplace.visualstudio.com/items?itemName=quicktype.quicktype)
  * `quicktype` infers types from sample JSON data, then outputs strongly typed models and serializers for working with that data in your desired programming language. For more explanation, read [A first look at quicktype](http://blog.quicktype.io/first-look/).
  * It supports `C#`, `Go`, `C++`, `Java`, `TypeScript`, `Swift`, `Elm`, and `JSON Schema`.  I have to say THIS IS AWESOME! Just try it.
  * For simple JSON document, I still using [JSON to TS](https://marketplace.visualstudio.com/items?itemName=MariusAlchimavicius.json-to-ts).  If the JSON document are more complex, [Paste JSON as Code](https://marketplace.visualstudio.com/items?itemName=quicktype.quicktype) is the best choice.

## 6.1.1 - 2018-06-11

* [Beautify](https://marketplace.visualstudio.com/items?itemName=HookyQR.beautify): The built-in `html.format.unformatted` is normal now.  So I deleted one recommended settings in the `README.md` file.

## 6.1.0 - 2018-05-14

* [Angular v6 Snippets](https://marketplace.visualstudio.com/items?itemName=johnpapa.Angular2): Renamed `docker-angular-multi-stage` to `docker-angular-node-multi-stage` for an node.js Dockerfile with Angular

## 6.0.1 - 2018-05-08

* Update README.md

## 6.0.0 - 2018-05-06

* Updated version to `v6.0.0` to match Angular v6
* Update README.md to align with the latest Angular v6 changes

## 1.3.2 - 2018-04-30

* Update README.md

## 1.3.1 - 2018-04-27

* Add [Git History](https://marketplace.visualstudio.com/items?itemName=donjayamanne.githistory)
  * This helps you view and search git log along with the graph and details. Awesome!
  * It also support **Compare**, **Cherry pick**, **Revert**, **Create branches from a commits** actions.

## 1.3.0 - 2018-04-26

* Add [TODO Highlight](https://marketplace.visualstudio.com/items?itemName=wayou.vscode-todo-highlight)
* Removed [Output Colorizer](https://marketplace.visualstudio.com/items?itemName=IBM.output-colorizer)

## 1.2.1 - 2018-04-14

* Add [Move TS - Move TypeScript files and update relative imports](https://marketplace.visualstudio.com/items?itemName=stringham.move-ts)
* Add [RxJS Explorer](http://reactive.how/rxjs/explorer) in the README

## 1.1.0 - 2018-04-04

* Since from VSCode 1.18 has built-in [Auto Import for JavaScript and TypeScript](https://code.visualstudio.com/updates/v1_18#_auto-import-for-javascript-and-typescript) feature so I removed the following extensions.
  * [TypeScript Importer](https://marketplace.visualstudio.com/items?itemName=pmneo.tsimporter)
  * [TypeScript Toolbox](https://marketplace.visualstudio.com/items?itemName=DSKWRK.vscode-generate-getter-setter)

## 1.0.2 - 2018-02-28

* Add some notes about importing RxJS stuff

## 1.0.0 - 2018-02-07

* Change a new Icon for this extension. :-)

## 0.9.5 - 2018-01-30

* Updated README.md for many extensions.

## 0.9.4 - 2018-01-24

* Fix some README typo and bad grammer.

## 0.9.3 - 2018-01-19

* Removed [Prettier - JavaScript formatter](https://marketplace.visualstudio.com/items?itemName=esbenp.prettier-vscode) due to user complain.

## 0.9.1 - 2017-12-07

* Removed [Angular-io-Code](https://marketplace.visualstudio.com/items?itemName=NoHomey.angular-io-code)

## 0.9.0 - 2017-11-07

* Added [Prettier - JavaScript formatter](https://marketplace.visualstudio.com/items?itemName=esbenp.prettier-vscode)
  * An amazing JavaScript/CSS/GraphQL/Markdown formatter. Check [this](https://prettier.io) out!

## 0.8.2 - 2017-11-05

* Update `README.md`
* Added [Angular Component Extension](https://marketplace.visualstudio.com/items?itemName=onixie.angular-component-extension) to the optional extension suggestion list.

## 0.8.1 - 2017-09-11

* Update `README.md`
* Changed VS Code dependency to v1.15 and above.

## 0.8.0 - 2017-09-10

* Remove [Auto Close Tag](https://marketplace.visualstudio.com/items?itemName=formulahendry.auto-close-tag)
  * From VS Code 1.16, it has built-in **Auto Close Tag** feature.

## 0.7.7 - 2017-09-07

* Update `README.md` only

## 0.7.0 - 2017-07-23

* Remove [HTML Snippets](https://marketplace.visualstudio.com/items?itemName=abusaidm.html-snippets)

## 0.6.1 - 2017-06-08

* Update `README.md` only

## 0.6.0 - 2017-06-09

* Remove [Better Merge](https://marketplace.visualstudio.com/items?itemName=pprice.better-merge)
  * Because this extension has been built-in Visual Studio Code v1.13.

## 0.5.4 - 2017-06-08

* Update `README.md` only

## 0.5.3 - 2017-06-04

* Remove [IntelliSense for CSS class names](https://marketplace.visualstudio.com/items?itemName=Zignd.html-css-class-completion)
  * The current version of this extension will broken Angular development.
  * All the IntelliSense will be disabled due to [unknown reason](https://github.com/zignd/HTML-CSS-Class-Completion/issues/58).
  * After this extension become stable, it'll add it back someday.

## 0.5.2 - 2017-06-04

* Add [TypeScript Toolbox](https://marketplace.visualstudio.com/items?itemName=DSKWRK.vscode-generate-getter-setter)
  * Suit for import types including node_modules

## 0.5.0 - 2017-06-04

* Add [TypeScript Importer](https://marketplace.visualstudio.com/items?itemName=pmneo.tsimporter)
  * Suit for import TypeScript types from current project except for node_modules!
* Remove [Auto Import - ES6 & TS](https://marketplace.visualstudio.com/items?itemName=moppitz.vscode-extension-auto-import)
  * This extension is too buggy.

## 0.4.0 - 2017-05-27

* Add [JSON to TS](https://marketplace.visualstudio.com/items?itemName=MariusAlchimavicius.json-to-ts)
* Add [Document This](https://marketplace.visualstudio.com/items?itemName=joelday.docthis)
* Remove [TypeScript Toolbox](https://marketplace.visualstudio.com/items?itemName=DSKWRK.vscode-generate-getter-setter)
  * Auto import feature is buggy.
* Remove [Git Lens](https://marketplace.visualstudio.com/items?itemName=eamodio.gitlens)
  * It's too informative.
* Remove [AngularDoc for Visual Studio Code](https://marketplace.visualstudio.com/items?itemName=AngularDoc.angulardoc-vscode)
  * Not always needed. It can be installed when it's needed.

## 0.3.2 - 2017-05-17

* Update `README.md` only

## 0.3.1 - 2017-05-16

* Add [Angular v4 TypeScript Snippets](https://marketplace.visualstudio.com/items?itemName=johnpapa.Angular2)

## 0.3.0 - 2017-05-14

* Add [Angular 2+ Snippets - TypeScript, Html, ngRx, Angular Flex Layout & Testing](https://marketplace.visualstudio.com/items?itemName=Mikael.Angular-BeastCode)
  * 110 Angular 2+ Snippets (TypeScript, Html, ngRx, Angular Flex Layout & Testing) Updated for v2.4.11 & v4.0.0
  * Remember there is a setting `"editor.snippetSuggestions": "top"` for seeing extension snippets on **top**.
* Remove [Angular v4 TypeScript Snippets](https://marketplace.visualstudio.com/items?itemName=johnpapa.Angular2)

## 0.2.0 - 2017-05-11

* Add [Auto Close Tag](https://marketplace.visualstudio.com/items?itemName=formulahendry.auto-close-tag)
* Add [TSLint](https://marketplace.visualstudio.com/items?itemName=eg2.tslint)
* Add [CSS Peek](https://marketplace.visualstudio.com/items?itemName=pranaygp.vscode-css-peek)
* Add [Git Lens](https://marketplace.visualstudio.com/items?itemName=eamodio.gitlens)
* Add [Better Merge](https://marketplace.visualstudio.com/items?itemName=pprice.better-merge)
* Remove [Document This](https://marketplace.visualstudio.com/items?itemName=joelday.docthis)
  * The [Auto JSDoc comments](https://code.visualstudio.com/updates/v1_10#_auto-jsdoc-comments) feature has been implemented in Visual Studio Code [February 2017 (version 1.10)](https://code.visualstudio.com/updates/v1_10).
* Remove [Auto-Open Markdown Preview](https://marketplace.visualstudio.com/items?itemName=hnw.vscode-auto-open-markdown-preview)
  * Hit `Ctrl+K V` will open MarkDown preview by default.

## 0.1.2 - 2017-05-10

* Initial release
