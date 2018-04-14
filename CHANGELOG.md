# Change Log

All notable changes to the "angular-extension-pack" extension pack will be documented in this file.

## 1.2.0 - 2018-04-14

* Add [Move TS - Move TypeScript files and update relative imports](https://marketplace.visualstudio.com/items?itemName=stringham.move-ts)

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
