# Ionic Snippets for VS Code

[![Visual Studio Marketplace](https://vsmarketplacebadge.apphb.com/version-short/fivethree.vscode-ionic-snippets.svg?style=flat-square)](https://marketplace.visualstudio.com/items?itemName=fivethree.vscode-ionic-snippets)
[![Visual Studio Marketplace](https://vsmarketplacebadge.apphb.com/installs-short/fivethree.vscode-ionic-snippets.svg?style=flat-square)](https://marketplace.visualstudio.com/items?itemName=fivethree.vscode-ionic-snippets)

Visual Studio Code Extension adds TypeScript and HTML snippets for Ionic 4.

All code snippets are based on and follow the [Ionic 4 Api](https://beta.ionicframework.com/docs/api).

## Using Snippets for Ionic 4

Type part of a snippet, press enter, and the snippet unfolds.

### Overview
* [Snippet Prefix](https://github.com/fivethree-team/vscode-ionic-snippets#snippet-prefix)
* [HTML Snippets](https://github.com/fivethree-team/vscode-ionic-snippets#html-snippets)
* [HTML Properties](https://github.com/fivethree-team/vscode-ionic-snippets#html-properties)
* [CSS Utilities](https://github.com/fivethree-team/vscode-ionic-snippets#css-utilities)
* [SCSS Snippets](https://github.com/fivethree-team/vscode-ionic-snippets#scss-snippets)
* [Typescript Snippets](https://github.com/fivethree-team/vscode-ionic-snippets#typescript-snippets)

### Snippet Prefix

| Prefix | Description |
| ------- | ----------|
| `i-` | Ionic Snippets |

### HTML Snippets

| Snippet                      | Purpose                                                      |
| ---------------------------- | ------------------------------------------------------------ |
| `i-anchor`                | `<ion-anchor>`                                                    |
| `i-app`                | `<ion-app>`                                                    |
| `i-avatar`                | `<ion-avatar>`                                                    |
| `i-back-button`                | `<ion-back-button>`                                                    |
| `i-back-button-default`                | `<ion-back-button>` w/ defaultHref                                                |
| `i-backdrop`                | `<ion-backdrop>`                                                    |
| `i-badge`                | `<ion-badge>`                                                    |
| `i-button`                | `<ion-button>`                                                    |
| `i-button-props`                | `<ion-button>` with fill and shape properties                                                    |
| `i-button-icon-only`                | `<ion-button>` icon only                                                    |
| `i-button-w-icon`                | `<ion-button>` w/ icon                                                    |
| `i-buttons`                | `<ion-buttons>`                                                    |
| `i-card`                | `<ion-card>`                                                    |
| `i-card`                | `<ion-card>` w/ `<ion-card-header>` and `<ion-card-content>`                                                    |
| `i-card-content`                | `<ion-card-content>`                                                    |
| `i-card-header`                | `<ion-card-header>`                                                    |
| `i-card-subtitle`                | `<ion-card-subtitle>`                                                    |
| `i-card-title`                | `<ion-card-title>`                                                    |
| `i-checkbox`                | `<ion-checkbox>`                                                    |
| `i-chip`                | `<ion-chip>`                                                    |
| `i-chip-avatar`                | `<ion-chip>` w/ `<ion-avatar>`                                                    |
| `i-chip-button`                | `<ion-chip-button>`                                                    |
| `i-chip-icon`                | `<ion-chip>` w/ `<ion-icon>` at the start                                                    |
| `i-chip-icon-end`                | `<ion-chip>` w/ `<ion-icon>` at the end                                                  |
| `i-col`                | `<ion-col>`                                                    |
| `i-col-offset`                | Ionic `<ion-col>` `[offset]` property selection                                 |
| `i-col-pull`                | Ionic `<ion-col>` `[pull]` property selection                                 |
| `i-col-push`                | Ionic `<ion-col>` `[push]` property selection                                 |
| `i-col-size`                | Ionic `<ion-col>` `[size]` property selection                                 |
| `i-content`                | `<ion-content>`                                                    |
| `i-content-events`                | `<ion-content>` w/ events                                                    |
| `i-datetime`                | `<ion-datetime>`                                                |
| `i-fab`                | `<ion-fab>` w/ `<ion-fab-button>`                                                    |
| `i-fab-button`                | `<ion-fab-button>`                                                    |
| `i-fab-list`                | `<ion-fab-list>`                                                    |
| `i-fab-list-full`                | `<ion-fab>` w/ `<ion-fab-list>`                                                    |
| `i-footer`                | `<ion-footer>`                                                    |
| `i-form`                | `<ion-form>` w/ `<ion-input>` and formGroup                                                    |
| `i-form-error`                | `<ion-form>` w/ `<ion-input>` and formGroup including error text                                                    |
| `i-form-input`                | `<ion-item>` w/ `<ion-input>` and formControlName                                                    |
| `i-form-input-error`                | `<ion-item>` w/ `<ion-input>` and formControlName including error text                                                    |
| `i-grid`                | `<ion-grid>` w/ `<ion-row>` and `<ion-col>`                                                    |
| `i-header`                | `<ion-header>`                                                   |
| `i-icon`                | `<ion-icon>`                                                    |
| `i-img`                | `<ion-img>` lazyily load an image                                                   |
| `i-infinite-scroll`                | `<ion-infinite-scroll>` w/ `<ion-infinite-scroll-content>`                                                   |
| `i-input`                | `<ion-input>` w/ type and placeholder                                                    |
| `i-item`                | `<ion-item>` w/ `<ion-label>`                                                    |
| `i-item-avatar`                | `<ion-item>` w/ `<ion-avatar>`                                                    |
| `i-item-badge`                | `<ion-item>` w/ `<ion-badge>`                                                    |
| `i-item-checkbox`                | `<ion-item>` w/ `<ion-checkbox>`                                                    |
| `i-item-divider`                | `<ion-item-divider>` w/ `<ion-label>`                                                    |
| `i-item-group`                | `<ion-item-group>` w/ `<ion-item-divider>` and `<ion-item>`                                                    |
| `i-item-input`                | `<ion-item>` w/ `<ion-input>`                                                    |
| `i-item-option`                | `<ion-item-option>`                                                  |
| `i-item-option-w-icon`                | `<ion-item-option>` w/ icon                                                |
| `i-item-option-icon-only`                | `<ion-item-option>` w/ icon only                                              |
| `i-item-option-expandable`                | `<ion-item-option>` w/ expandable option                                             |
| `i-item-options`                | `<ion-item-options>`                                             |
| `i-item-sliding`                | `<ion-item-sliding>`                                             |
| `i-item-radio`                | `<ion-item>` w/ `<ion-radio>`                                                    |
| `i-item-toggle`                | `<ion-item>` w/ `<ion-toggle>`                                                    |
| `i-label`                | `<ion-label>`                                                    |
| `i-label-position`                | `<ion-label>` w/ position selection                                                  |
| `i-list`                | `<ion-list>` w/ two `<ion-item>`                                                    |
| `i-list-header`                | `<ion-list-header>`                                                    |
| `i-list-input`                | `<ion-item>` w/ two `<ion-item>`                                                    |
| `i-menu`                | `<ion-menu>` w/ `<ion-header>` and `<ion-content>`                                                   |
| `i-menu-advanced`                | `<ion-menu>` w/ `<ion-header>`, `<ion-content>` and `<ion-footer>`                                                    |
| `i-menu-button`                | `<ion-menu-button>`                                                    |
| `i-note`                | `<ion-note>`                                                    |
| `i-radio`                | `<ion-radio>`                                                    |
| `i-radio-checked`                | `<ion-radio>` checked                                                    |
| `i-radio-group`                | `<ion-radio-group>`                                                    |
| `i-row`                | `<ion-row>` w/ `<ion-col>`                                                   |
| `i-searchbar`                | `<ion-searchbar>`                                                   |
| `i-segment`                | `<ion-segment>`                                                   |
| `i-segment-button`                | `<ion-segment-button>`                                                   |
| `i-select`                | `<ion-select>` w/ `<ion-select-option>`                                                   |
| `i-select-option`                | `<ion-select-option>`                                                   |
| `i-skeleton-text`                | `<ion-skeleton-text>`                                                   |
| `i-slide`                | `<ion-slide>`                                                   |
| `i-slides`                | `<ion-slides>` w/ `<ion-slide>`                                                |
| `i-spinner`                | `<ion-spinner>`                                              |
| `i-split-pane`                | `<ion-split-pane>`                                              |
| `i-split-pane-advanced`                | `<ion-split-pane>` w/ a menu including `<ion-header>`, `<ion-content>` and `<ion-footer>`                                           |
| `i-tab`                | `<ion-tab>`                                              |
| `i-tab-bar`                | `<ion-tab-bar>`                                              |
| `i-tab-button`                | `<ion-tab-button>` connected to `<ion-tab>`                                            |
| `i-tab-button-only-button`                | `<ion-tab-button>` just a button                                            |
| `i-tab-button-only-link`                | `<ion-tab-button>` just a link                                            |
| `i-tab-content`                | `<ion-tab>` custom content                                            |
| `i-tabs`                | `<ion-tabs>`                                              |
| `i-text`                | `<ion-text>`                                              |
| `i-textarea`                | `<ion-textarea>`                                              |
| `i-thumbnail`                | `<ion-thumbnail>`                                              |
| `i-title`                | `<ion-title>`                                              |
| `i-toggle`                | `<ion-toggle>`                                              |
| `i-toolbar`                | `<ion-toolbar>`                                              |
| `i-virtual-scroll`                | `<ion-virtual-scroll>`                                              |
| `i-virtual-scroll-w-custom-component`                | `<ion-virtual-scroll>` with `<div>` wrapping a custom component                                              |
| `i-virtual-scroll-w-header`                | `<ion-virtual-scroll>` with header function                                          |

**[⬆ back to top](#overview)**

### HTML Properties

| Snippet                      | Purpose                                                      |
| ---------------------------- | ------------------------------------------------------------ |
| `i-click`                | (click) event                                              |
| `i-color`                | Ionic color property w/ selection                                              |
| `i-scrollEvents`                | Ionic [scrollEvents] binding for `<ion-content>`                                          |
| `i-slot`                | Ionic slot property w/ selection                                |

**[⬆ back to top](#overview)**

### CSS Utilities

| Snippet                      | Purpose                                                      |
| ---------------------------- | ------------------------------------------------------------ |
| `i-text-alignment`                | Text alignment such as left, right, center                                                   |

**[⬆ back to top](#overview)**

### SCSS Snippets

| Snippet                      | Purpose                                                      |
| ---------------------------- | ------------------------------------------------------------ |
| `i-color`                | Ionic scss color variables w/ color selection                                                    |
| `i-color-custom`                | Custom Color can be used as color property `color='favorite'`, add to variables.scss                                                    |
| `i-color-custom-root`                | Custom Color add to `:root` in variables.scss                                                   |
| `i-dark-mode`                | Dark mode example for Mac OS                                                   |
| `i-dark-mode-media-query`                | Dark mode media query for Mac OS                                                   |
| `i-root`                | `:root { }`                                                    |
| `i-stepped-color`                | Stepped colors add to `:root`                                                  |


**[⬆ back to top](#overview)**

### Typescript Snippets

| Snippet                      | Purpose                                                      |
| ---------------------------- | ------------------------------------------------------------ |
| `i-action-sheet`                | Ionic action sheet dialog method                                                  |
| `i-action-sheet-ctrl`                | Ionic ActionSheetController    |
| `i-alert`                | Ionic alert dialog method                                                  |
| `i-alert-confirm`                | Ionic alert confirm dialog method                                                  |
| `i-alert-ctrl`                | Ionic AlertController                                                 |
| `i-ctrl-import`                | Imports Ionic Controller from `@ionic/angular` package                                               |
| `i-form`                | Simple form group                                                 |
| `i-form-builder`                | FormBuilder                                                 |
| `i-form-group`                | FormGroup instance                                                 |
| `i-form-value`                | Get value for formControlName `form.get('email')`                                               |
| `i-infinite-scroll-load-data`                | Method to load more data with `complete` and `disabled` call                                             |
| `i-infinite-scroll-toggle`                | Method to toggle `disabled` of InfiniteScroll                                             |
| `i-infinite-scroll-viewchild`                | Viewchild for InfiniteScroll                                             |
| `i-loading`                | Ionic loading dialog                                             |
| `i-loading-ctrl`                | Ionic LoadingController                                             |
| `i-modal`                | Ionic modal dialog method                                                 |
| `i-modal-will-dismiss`                | Ionic modal dialog method wit `onWillDismiss`                                              |
| `i-modal-ctrl`                | Ionic ModalController                                                 |
| `i-popover`                | Ionic popover dialog method                                                 |
| `i-popover-ctrl`                | Ionic PopoverController                                                 |
| `i-on-did-dismiss`                | Ionic `onDidDismiss` for dialogs                                                 |
| `i-on-did-dismiss-data`                | Ionic `onDidDismiss` for dialogs returning data                                                 |
| `i-on-will-dismiss`                | Ionic `onWillDismiss` for dialogs                                                 |
| `i-on-will-dismiss-data`                | Ionic `onWillDismiss` for dialogs returning data                                                |
| `i-toast`                | Ionic toast notification method                                                 |
| `i-toast-ctrl`                | Ionic ToastController                                                 |
| `i-virtual-scroll-header-fn`                | Ionic virtual scroll header function                                                 |

**[⬆ back to top](#overview)**
