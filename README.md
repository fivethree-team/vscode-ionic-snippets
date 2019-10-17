<p align="center">
  <a href="https://marketplace.visualstudio.com/items?itemName=fivethree.vscode-ionic-snippets" target="blank"><img src="https://raw.githubusercontent.com/fivethree-team/vscode-ionic-snippets/master/images/banner.png" width="460px" alt="Ionic 4 VS Code Snippets" /></a>
</p>

# Ionic Snippets for VS Code

[![Visual Studio Marketplace](https://vsmarketplacebadge.apphb.com/version-short/fivethree.vscode-ionic-snippets.svg?style=flat-square)](https://marketplace.visualstudio.com/items?itemName=fivethree.vscode-ionic-snippets)
[![Visual Studio Marketplace](https://vsmarketplacebadge.apphb.com/installs-short/fivethree.vscode-ionic-snippets.svg?style=flat-square)](https://marketplace.visualstudio.com/items?itemName=fivethree.vscode-ionic-snippets)

Boost your [Ionic 4](https://ionicframework.com/) development with snippets for [VS Code](https://code.visualstudio.com/)

✅ Fast templates with snippets of ~100 Ionic components  
✅ Easy custom theming with CSS properties  
✅ Framework support for [angular](https://angular.io/), [stenciljs](https://stenciljs.com/) and [vuejs](https://vuejs.org/)

All code snippets are based on and follow the [Ionic 4 Api](https://ionicframework.com/docs/api).

## Using Snippets for Ionic 4

Type part of a snippet, press enter, and the snippet unfolds.

## Framework

### Snippet Prefix

| Framework               | Prefix | Status |
| ----------------------- | ------ | ------ |
| Angular                 | `i-`   | ✅     |
| Stenciljs               | `i-`   | ✅     |
| Vanilla Javascript/Html | `i-`   | ✅     |
| React                   | `ir-`  | 🚧     |
| Vue                     | `i-`   | 🔶     |

✅ — Supported  
🔶 — Partial support  
🚧 — Under development

### Overview

- [Ionic Snippets for VS Code](#ionic-snippets-for-vs-code)
  - [Using Snippets for Ionic 4](#using-snippets-for-ionic-4)
  - [Framework](#framework)
    - [Snippet Prefix](#snippet-prefix)
    - [Overview](#overview)
    - [HTML Snippets](#html-snippets)
    - [HTML Properties](#html-properties)
    - [CSS Utilities](#css-utilities)
    - [SCSS Snippets](#scss-snippets)
    - [Typescript Snippets](#typescript-snippets)

### HTML Snippets

| Snippet                               | Purpose                                                                                                                              |
| ------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------ |
| `i-app`                               | `<ion-app>`                                                                                                                          |
| `i-avatar`                            | `<ion-avatar>`                                                                                                                       |
| `i-back-button`                       | `<ion-back-button>`                                                                                                                  |
| `i-back-button-default`               | `<ion-back-button>` w/ defaultHref                                                                                                   |
| `i-backdrop`                          | `<ion-backdrop>`                                                                                                                     |
| `i-backdrop-props`                    | `<ion-backdrop>` w/ properties                                                                                                       |
| `i-badge`                             | `<ion-badge>`                                                                                                                        |
| `i-button`                            | `<ion-button>`                                                                                                                       |
| `i-button-props`                      | `<ion-button>` with fill and shape properties                                                                                        |
| `i-button-icon-only`                  | `<ion-button>` icon only                                                                                                             |
| `i-button-w-icon`                     | `<ion-button>` w/ icon                                                                                                               |
| `i-buttons`                           | `<ion-buttons>`                                                                                                                      |
| `i-card`                              | `<ion-card>`                                                                                                                         |
| `i-card-loop`                         | `<ion-card *ngFor>`                                                                                                                  |
| `i-card-full`                         | `<ion-card>` w/ `<ion-card-header>` and `<ion-card-content>`                                                                         |
| `i-card-content`                      | `<ion-card-content>`                                                                                                                 |
| `i-card-header`                       | `<ion-card-header>`                                                                                                                  |
| `i-card-subtitle`                     | `<ion-card-subtitle>`                                                                                                                |
| `i-card-title`                        | `<ion-card-title>`                                                                                                                   |
| `i-checkbox`                          | `<ion-checkbox>`                                                                                                                     |
| `i-chip`                              | `<ion-chip>`                                                                                                                         |
| `i-chip-avatar`                       | `<ion-chip>` w/ `<ion-avatar>`                                                                                                       |
| `i-chip-icon-start`                   | `<ion-chip>` w/ `<ion-icon>` at the start                                                                                            |
| `i-chip-icon-end`                     | `<ion-chip>` w/ `<ion-icon>` at the end                                                                                              |
| `i-col`                               | `<ion-col>`                                                                                                                          |
| `i-col-offset`                        | Ionic `<ion-col>` `[offset]` property selection                                                                                      |
| `i-col-offset-responsive`             | Ionic `<ion-col>` `[offset]` property selection w/ breakpoints                                                                       |
| `i-col-pull`                          | Ionic `<ion-col>` `[pull]` property selection                                                                                        |
| `i-col-pull-responsive`               | Ionic `<ion-col>` `[pull]` property selection w/ breakpoints                                                                         |
| `i-col-push`                          | Ionic `<ion-col>` `[push]` property selection                                                                                        |
| `i-col-push-responsive`               | Ionic `<ion-col>` `[push]` property selection w/ breakpoints                                                                         |
| `i-col-size`                          | Ionic `<ion-col>` `[size]` property selection                                                                                        |
| `i-col-size-responsive`               | Ionic `<ion-col>` `[size]` property selection w/ breakpoints                                                                         |
| `i-content`                           | `<ion-content>`                                                                                                                      |
| `i-content-events`                    | `<ion-content>` w/ events                                                                                                            |
| `i-datetime`                          | `<ion-datetime>`                                                                                                                     |
| `i-fab`                               | `<ion-fab>` w/ `<ion-fab-button>`                                                                                                    |
| `i-fab-button`                        | `<ion-fab-button>`                                                                                                                   |
| `i-fab-list`                          | `<ion-fab-list>`                                                                                                                     |
| `i-fab-list-full`                     | `<ion-fab>` w/ `<ion-fab-list>`                                                                                                      |
| `i-footer`                            | `<ion-footer>`                                                                                                                       |
| `i-form`                              | `<ion-form>` w/ `<ion-input>` and formGroup                                                                                          |
| `i-form-error`                        | `<ion-form>` w/ `<ion-input>` and formGroup including error text                                                                     |
| `i-form-input`                        | `<ion-item>` w/ `<ion-input>` and formControlName                                                                                    |
| `i-form-input-error`                  | `<ion-item>` w/ `<ion-input>` and formControlName including error text                                                               |
| `i-grid`                              | `<ion-grid>` w/ `<ion-row>` and `<ion-col>`                                                                                          |
| `i-header`                            | `<ion-header>`                                                                                                                       |
| `i-icon`                              | `<ion-icon>`                                                                                                                         |
| `i-img`                               | `<ion-img>` lazyily load an image                                                                                                    |
| `i-infinite-scroll`                   | `<ion-infinite-scroll>` w/ `<ion-infinite-scroll-content>`                                                                           |
| `i-input`                             | `<ion-input>` w/ type and placeholder                                                                                                |
| `i-item`                              | `<ion-item>` w/ `<ion-label>`                                                                                                        |
| `i-item-avatar`                       | `<ion-item>` w/ `<ion-avatar>`                                                                                                       |
| `i-item-badge`                        | `<ion-item>` w/ `<ion-badge>`                                                                                                        |
| `i-item-checkbox`                     | `<ion-item>` w/ `<ion-checkbox>`                                                                                                     |
| `i-item-divider`                      | `<ion-item-divider>` w/ `<ion-label>`                                                                                                |
| `i-item-floating-label`               | `<ion-item>` w/ `<p>` and `<h2>` wrapped by `<ion-label>`                                                                            |
| `i-item-group`                        | `<ion-item-group>` w/ `<ion-item-divider>` and `<ion-item>`                                                                          |
| `i-item-icon`                         | `<ion-item>` w/ `<ion-icon>`                                                                                                         |
| `i-item-input`                        | `<ion-item>` w/ `<ion-input>`                                                                                                        |
| `i-item-option`                       | `<ion-item-option>`                                                                                                                  |
| `i-item-option-w-icon`                | `<ion-item-option>` w/ icon                                                                                                          |
| `i-item-option-icon-only`             | `<ion-item-option>` w/ icon only                                                                                                     |
| `i-item-option-expandable`            | `<ion-item-option>` w/ expandable option                                                                                             |
| `i-item-options`                      | `<ion-item-options>`                                                                                                                 |
| `i-item-sliding`                      | `<ion-item-sliding>`                                                                                                                 |
| `i-item-radio`                        | `<ion-item>` w/ `<ion-radio>`                                                                                                        |
| `i-item-toggle`                       | `<ion-item>` w/ `<ion-toggle>`                                                                                                       |
| `i-label`                             | `<ion-label>`                                                                                                                        |
| `i-label-floating`                    | `<ion-label>` w/ `<p>` and `<h2>`                                                                                                    |
| `i-label-position`                    | `<ion-label>` w/ position selection                                                                                                  |
| `i-list`                              | `<ion-list>`                                                                                                                         |
| `i-list-header`                       | `<ion-list-header>`                                                                                                                  |
| `i-list-input`                        | `<ion-item>` w/ two `<ion-item>`                                                                                                     |
| `i-menu`                              | `<ion-menu>` w/ `<ion-header>` and `<ion-content>`                                                                                   |
| `i-menu-advanced`                     | `<ion-menu>` w/ `<ion-header>`, `<ion-content>` and `<ion-footer>`                                                                   |
| `i-menu-button`                       | `<ion-menu-button>`                                                                                                                  |
| `i-nav`                               | `<ion-nav>` standalone Nav component                                                                                                 |
| `i-nav-link`                          | `<ion-nav-link>` navigate to a component                                                                                             |
| `i-note`                              | `<ion-note>`                                                                                                                         |
| `i-progress`                          | `<ion-progress>`                                                                                                                     |
| `i-radio`                             | `<ion-radio>`                                                                                                                        |
| `i-radio-checked`                     | `<ion-radio>` checked                                                                                                                |
| `i-radio-group`                       | `<ion-radio-group>`                                                                                                                  |
| `i-range`                             | `<ion-range>`                                                                                                                        |
| `i-range-icon`                        | `<ion-range>` w/ `<ion-icon>`                                                                                                        |
| `i-range-label`                       | `<ion-range>` w/ `<ion-label>`                                                                                                       |
| `i-refresher`                         | `<ion-refresher>`                                                                                                                    |
| `i-refresher-content`                 | `<ion-refresher>` w/ `<ion-refresher-content>` options                                                                               |
| `i-refresher-events`                  | `<ion-refresher>` w/ all events                                                                                                      |
| `i-reorder`                           | `<ion-reorder>`                                                                                                                      |
| `i-reorder-icon`                      | `<ion-reorder>` w/ `<ion-icon>`                                                                                                      |
| `i-reorder-item`                      | `<ion-reorder>` entire `<ion-item>`'s                                                                                                |
| `i-reorder-group`                     | `<ion-reorder-group>`                                                                                                                |
| `i-ripple-effect`                     | `<ion-ripple-effect>`                                                                                                                |
| `i-route`                             | `<i-route>` used inside of `<ion-router>` and should only be used with vanilla and Stencil JavaScript projects                       |
| `i-route-redirect`                    | `<ion-route-redirect>` can only be use inside of `<ion-router>` and should only be used with vanilla and Stencil JavaScript projects |
| `i-router`                            | `<ion-router>` only once per App and should only be used with vanilla and Stencil JavaScript projects                                |
| `i-router-outlet`                     | `<i-router-outlet>` should only be used with Angular projects                                                                        |
| `i-row`                               | `<ion-row>` w/ `<ion-col>`                                                                                                           |
| `i-searchbar`                         | `<ion-searchbar>`                                                                                                                    |
| `i-segment`                           | `<ion-segment>`                                                                                                                      |
| `i-segment-button`                    | `<ion-segment-button>`                                                                                                               |
| `i-select`                            | `<ion-select>` w/ `<ion-select-option>`                                                                                              |
| `i-select-loop`                       | `<ion-select>` w/ `<ion-select-option *ngFor>`                                                                                       |
| `i-select-interface-options`          | `<ion-select>` w/ `interfaceOptions`                                                                                                 |
| `i-select-interface-options-loop`     | `<ion-select>` w/ `interfaceOptions` and `<ion-select-option *ngFor>`                                                                |
| `i-select-option`                     | `<ion-select-option>`                                                                                                                |
| `i-select-option-loop`                | `<ion-select-option *ngFor>`                                                                                                         |
| `i-skeleton-text`                     | `<ion-skeleton-text>`                                                                                                                |
| `i-slide`                             | `<ion-slide>`                                                                                                                        |
| `i-slides`                            | `<ion-slides>` w/ `<ion-slide>`                                                                                                      |
| `i-slides-options`                    | `<ion-slides>` w/ options                                                                                                            |
| `i-spinner`                           | `<ion-spinner>`                                                                                                                      |
| `i-split-pane`                        | `<ion-split-pane>`                                                                                                                   |
| `i-split-pane-advanced`               | `<ion-split-pane>` w/ a menu including `<ion-header>`, `<ion-content>` and `<ion-footer>`                                            |
| `i-tab`                               | `<ion-tab>`                                                                                                                          |
| `i-tab-bar`                           | `<ion-tab-bar>`                                                                                                                      |
| `i-tab-button`                        | `<ion-tab-button>` connected to `<ion-tab>`                                                                                          |
| `i-tab-button-only-button`            | `<ion-tab-button>` just a button                                                                                                     |
| `i-tab-button-only-link`              | `<ion-tab-button>` just a link                                                                                                       |
| `i-tab-content`                       | `<ion-tab>` custom content                                                                                                           |
| `i-tabs`                              | `<ion-tabs>`                                                                                                                         |
| `i-text`                              | `<ion-text>`                                                                                                                         |
| `i-textarea`                          | `<ion-textarea>`                                                                                                                     |
| `i-textarea-w-placeholder`            | `<ion-textarea>` w/ placeholder                                                                                                      |
| `i-textarea-w-label`                  | `<ion-textarea>` w/ `<ion-label>`                                                                                                    |
| `i-thumbnail`                         | `<ion-thumbnail>`                                                                                                                    |
| `i-title`                             | `<ion-title>`                                                                                                                        |
| `i-toggle`                            | `<ion-toggle>`                                                                                                                       |
| `i-toolbar`                           | `<ion-toolbar>`                                                                                                                      |
| `i-virtual-scroll`                    | `<ion-virtual-scroll>`                                                                                                               |
| `i-virtual-scroll-w-custom-component` | `<ion-virtual-scroll>` with `<div>` wrapping a custom component                                                                      |
| `i-virtual-scroll-w-header`           | `<ion-virtual-scroll>` with header function                                                                                          |

**[⬆ back to top](#overview)**

### HTML Properties

| Snippet          | Purpose                                          |
| ---------------- | ------------------------------------------------ |
| `i-click`        | (click) event                                    |
| `i-color`        | Ionic color property w/ selection                |
| `i-scrollEvents` | Ionic [scrollEvents] binding for `<ion-content>` |
| `i-slot`         | Ionic slot property w/ selection                 |

**[⬆ back to top](#overview)**

### CSS Utilities

| Snippet                      | Purpose                                                                                                                     |
| ---------------------------- | --------------------------------------------------------------------------------------------------------------------------- |
| `i-align-items`              | CSS Utilities Flex Container Align Items                                                                                    |
| `i-align-self`               | CSS Utilities Flex Container Align Self                                                                                     |
| `i-flex-wrap`                | CSS Utilities Flex Container Flex Wrap                                                                                      |
| `i-float-element`            | CSS Utilities Float Elements                                                                                                |
| `i-float-element-responsive` | CSS Utilities Responsive Float Classes                                                                                      |
| `i-hide`                     | CSS Utilities Hide Element                                                                                                  |
| `i-hide-breakpoints`         | CSS Utilities Hide Element with Display Breakpoints                                                                         |
| `i-hide-sm`                  | CSS Utilities Hide Element sm. Applies the modifier to the element when min-width: 576px (up) or max-width: 576px (down).   |
| `i-hide-md`                  | CSS Utilities Hide Element md . Applies the modifier to the element when min-width: 768px (up) or max-width: 768px (down).  |
| `i-hide-lg`                  | CSS Utilities Hide Element lg. Applies the modifier to the element when min-width: 992px (up) or max-width: 992px (down).   |
| `i-hide-xl`                  | CSS Utilities Hide Element xl. Applies the modifier to the element when min-width: 1200px (up) or max-width: 1200px (down). |
| `i-justity-content`          | CSS Utilities Flex Container Justify Content                                                                                |
| `i-margin`                   | CSS Utilities Element Margin                                                                                                |
| `i-margin-type`              | CSS Utilities Element Margin Type                                                                                           |
| `i-no-margin`                | CSS Utilities Element No Margin                                                                                             |
| `i-padding`                  | CSS Utilities Element Padding                                                                                               |
| `i-padding-type`             | CSS Utilities Element Padding Type                                                                                          |
| `i-no-padding`               | CSS Utilities Element No Padding                                                                                            |
| `i-text-alignment`           | CSS Utilities Text Alignment                                                                                                |
| `i-text-responsive`          | CSS Utilities Responsive Text Classes for Alignment and Transformations                                                     |
| `i-text-transformation`      | CSS Utilities Text Transformation                                                                                           |

**[⬆ back to top](#overview)**

### SCSS Snippets

| Snippet                  | Purpose                                                                              |
| ------------------------ | ------------------------------------------------------------------------------------ |
| `i-action-sheet-props`   | Action Sheet CSS custom properties                                                   |
| `i-alert-props`          | Alert CSS custom properties                                                          |
| `i-anchor-props`         | Anchor CSS custom properties                                                         |
| `i-avatar-props`         | Avatar CSS custom properties                                                         |
| `i-back-button-props`    | Back Button CSS custom properties                                                    |
| `i-badge-props`          | Badge CSS custom properties                                                          |
| `i-button-props`         | Button CSS custom properties                                                         |
| `i-card-props`           | Card CSS custom properties                                                           |
| `i-card-subtitle-props`  | Card Subtitle CSS custom properties                                                  |
| `i-card-title-props`     | Card Title CSS custom properties                                                     |
| `i-checkbox-props`       | Checkbox CSS custom properties                                                       |
| `i-chip-props`           | Chip CSS custom properties                                                           |
| `i-col-props`            | Col CSS custom properties                                                            |
| `i-color`                | Ionic scss color variables w/ color selection                                        |
| `i-color-custom`         | Custom Color can be used as color property `color='favorite'`, add to variables.scss |
| `i-color-custom-root`    | Custom Color add to `:root` in variables.scss                                        |
| `i-content-props`        | Content CSS custom properties                                                        |
| `i-dark-theme`           | Ionic Dark Theme                                                                     |
| `i-datetime-props`       | Datetime CSS custom properties                                                       |
| `i-fab-button-props`     | Fab-Button CSS custom properties                                                     |
| `i-grid-props`           | Grid CSS custom properties                                                           |
| `i-icon-props`           | Icon CSS properties                                                                  |
| `i-input-props`          | Input CSS custom properties                                                          |
| `i-item-props`           | Item CSS custom properties                                                           |
| `i-item-divider-props`   | Item Divider CSS custom properties                                                   |
| `i-item-option-props`    | Item Option CSS custom properties                                                    |
| `i-label-props`          | Label CSS custom properties                                                          |
| `i-list-header-props`    | List Header CSS custom properties                                                    |
| `i-loading-props`        | Loading CSS custom properties                                                        |
| `i-menu-props`           | Menu CSS custom properties                                                           |
| `i-menu-button-props`    | Menu Button CSS custom properties                                                    |
| `i-modal-props`          | Modal CSS custom properties                                                          |
| `i-note-props`           | Note CSS custom properties                                                           |
| `i-picker-props`         | Picker CSS custom properties                                                         |
| `i-popover-props`        | Popover CSS custom properties                                                        |
| `i-prefers-color-scheme` | Media query for prefered-color-scheme                                                |
| `i-progress-bar-props`   | Progress Bar CSS custom properties                                                   |
| `i-radio-props`          | Radio CSS custom properties                                                          |
| `i-range-props`          | Range CSS custom properties                                                          |
| `i-rgba`                 | Add opacity to Ionic colors using `rgba(...)`                                        |
| `i-root`                 | `:root { }`                                                                          |
| `i-searchbar-props`      | Searchbar CSS custom properties                                                      |
| `i-segment-button-props` | Segment Button CSS custom properties                                                 |
| `i-select-props`         | Select CSS custom properties                                                         |
| `i-skeleton-text-props`  | Skeleton Text CSS custom properties                                                  |
| `i-sliders-props`        | Slides CSS custom properties                                                         |
| `i-spinner-props`        | Spinner CSS custom properties                                                        |
| `i-split-pane-props`     | Split Pane CSS custom properties                                                     |
| `i-stepped-color`        | Stepped colors add to `:root`                                                        |
| `i-tab-bar-props`        | Tab Bar CSS custom properties                                                        |
| `i-tab-button-props`     | Tab Button CSS custom properties                                                     |
| `i-textarea-props`       | Textarea CSS custom properties                                                       |
| `i-thumbnail-props`      | Thumbnail CSS custom properties                                                      |
| `i-title-props`          | Title CSS custom properties                                                          |
| `i-toast-props`          | Toast CSS custom properties                                                          |
| `i-toast-example`        | Toast CSS custom example style for success, warning or danger toasts                 |
| `i-toggle-props`         | Toggle CSS custom properties                                                         |
| `i-toolbar-props`        | Toolbar CSS custom properties                                                        |

**[⬆ back to top](#overview)**

### Typescript Snippets

| Snippet                       | Purpose                                                                                                                                            |
| ----------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------- |
| `i-action-sheet`              | Ionic action sheet method                                                                                                                          |
| `i-action-sheet-ctrl`         | Ionic ActionSheetController                                                                                                                        |
| `i-alert`                     | Ionic alert dialog method                                                                                                                          |
| `i-alert-confirm`             | Ionic alert confirm dialog method                                                                                                                  |
| `i-alert-ctrl`                | Ionic AlertController                                                                                                                              |
| `i-ctrl-import`               | Imports Ionic Controller from `@ionic/angular` package                                                                                             |
| `i-form`                      | Simple form group                                                                                                                                  |
| `i-form-builder`              | FormBuilder                                                                                                                                        |
| `i-form-group`                | FormGroup instance                                                                                                                                 |
| `i-form-value`                | Get value for formControlName `form.get('email')`                                                                                                  |
| `i-infinite-scroll-load-data` | Method to load more data with `complete` and `disabled` call                                                                                       |
| `i-infinite-scroll-toggle`    | Method to toggle `disabled` of InfiniteScroll                                                                                                      |
| `i-infinite-scroll-viewchild` | Viewchild for InfiniteScroll                                                                                                                       |
| `i-loading`                   | Ionic loading dialog                                                                                                                               |
| `i-loading-ctrl`              | Ionic LoadingController                                                                                                                            |
| `i-modal`                     | Ionic modal dialog method                                                                                                                          |
| `i-modal-dismiss`             | Ionic modal dialog with dismiss                                                                                                                    |
| `i-modal-ctrl`                | Ionic ModalController                                                                                                                              |
| `i-picker`                    | Ionic Picker                                                                                                                                       |
| `i-picker-colum`              | Ionic Picker Column                                                                                                                                |
| `i-picker-option`             | Ionic Picker Option                                                                                                                                |
| `i-picker-ctrl`               | Ionic PickerController                                                                                                                             |
| `i-popover`                   | Ionic popover dialog method                                                                                                                        |
| `i-popover-ctrl`              | Ionic PopoverController                                                                                                                            |
| `i-on-did-dismiss`            | Ionic `onDidDismiss` for dialogs                                                                                                                   |
| `i-on-did-dismiss-data`       | Ionic `onDidDismiss` for dialogs returning data                                                                                                    |
| `i-on-will-dismiss`           | Ionic `onWillDismiss` for dialogs                                                                                                                  |
| `i-on-will-dismiss-data`      | Ionic `onWillDismiss` for dialogs returning data                                                                                                   |
| `i-refresher-do-refresh`      | `<ion-refesher ionRefresh>` output handler method                                                                                                  |
| `i-reorder-do-reorder`        | `<ion-reorder ionItemReorder>` output handler method                                                                                               |
| `i-slides-options`            | Ionic slides options                                                                                                                               |
| `i-toast`                     | Ionic toast notification method                                                                                                                    |
| `i-toast-button`              | Ionic toast button                                                                                                                                 |
| `i-toast-w-buttons`           | Ionic toast notification w/ buttons                                                                                                                |
| `i-toast-w-options`           | Ionic toast notification w/ options                                                                                                                |
| `i-toast-ctrl`                | Ionic ToastController                                                                                                                              |
| `i-view-will-enter`           | `ionViewWillEnter` (1st) - Fired when entering a page (also if it’s come back from stack), subscribe to `Observables` here or in `ionViewDidEnter` |
| `i-view-did-enter`            | `ionViewDidEnter` (2nd) - Fired after entering (also if it’s come back from stack), subscribe to `Observables` here or in `ionViewWillEnter`       |
| `i-view-will-leave`           | `ionViewWillLeave` (3rd) - Fired if the page will leave (also if it’s keep in stack), cancel `Observables` here or in `ionViewDidLeave`            |
| `i-view-did-leave`            | `ionViewDidLeave` (4th) - Fired after the page was left (also if it’s keep in stack), cancel `Observables` here or in `ionViewWillLeave`           |
| `i-view-will-unload`          | `ionViewWillUnload` (5th) - In Angular not firing because here you have to use `ngOnDestroy`                                                       |
| `i-virtual-scroll-header-fn`  | Ionic virtual scroll header function                                                                                                               |

**[⬆ back to top](#overview)**
