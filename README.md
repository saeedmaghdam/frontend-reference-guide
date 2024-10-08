# Frontend Reference Guide

A **complete reference document** covering every class, utility, directive, and operator from **Bootstrap 5.3.3**, **Angular v18**, **RxJS 7.8.1**, and **Angular Material**. I’ll break down every category in a more extensive and exhaustive manner, aiming to cover all aspects in full detail.

---

# **Bootstrap 5.3.3 Full Reference**

### **Core Utilities**

#### **Display Classes**
- `.d-none`, `.d-inline`, `.d-inline-block`, `.d-block`, `.d-flex`, `.d-grid`
- Responsive Display: `.d-{sm, md, lg, xl, xxl}-{block, none, flex, grid}`
  
#### **Float Utilities**
- `.float-start`, `.float-end`, `.float-none`
- **Clearfix**: `.clearfix`

#### **Flexbox Utilities**
- `.flex-row`, `.flex-column`, `.flex-wrap`, `.flex-nowrap`, `.justify-content-start`, `.justify-content-center`, `.justify-content-end`, `.align-items-start`, `.align-items-center`
- `.align-self-start`, `.align-self-center`, `.flex-grow-1`, `.flex-shrink-1`

#### **Position Utilities**
- `.position-static`, `.position-relative`, `.position-absolute`, `.position-fixed`, `.position-sticky`
- `.top-0`, `.end-0`, `.bottom-0`, `.start-0`

#### **Overflow Utilities**
- `.overflow-auto`, `.overflow-hidden`, `.overflow-visible`, `.overflow-scroll`

#### **Visibility Utilities**
- `.visible`, `.invisible`

#### **Spacing Utilities**
- **Margin**: `.m-{0-5}`, `.mt-{0-5}`, `.mb-{0-5}`, `.ms-{0-5}`, `.me-{0-5}`
- **Padding**: `.p-{0-5}`, `.pt-{0-5}`, `.pb-{0-5}`, `.ps-{0-5}`, `.pe-{0-5}`

#### **Borders**
- **Border Width**: `.border`, `.border-0`, `.border-top-0`, `.border-end-0`, `.border-bottom-0`, `.border-start-0`
- **Border Colors**: `.border-primary`, `.border-secondary`, `.border-success`, `.border-info`, `.border-danger`, `.border-warning`
- **Rounded Borders**: `.rounded`, `.rounded-top`, `.rounded-end`, `.rounded-bottom`, `.rounded-start`, `.rounded-circle`, `.rounded-pill`

#### **Shadows**
- `.shadow-none`, `.shadow-sm`, `.shadow`, `.shadow-lg`

#### **Typography Utilities**
- **Text Alignment**: `.text-start`, `.text-center`, `.text-end`, `.text-wrap`, `.text-nowrap`
- **Text Transformations**: `.text-lowercase`, `.text-uppercase`, `.text-capitalize`
- **Font Weight**: `.fw-light`, `.fw-normal`, `.fw-bold`, `.fw-bolder`
- **Font Size**: `.fs-{1-6}`, `.fs-sm`, `.fs-lg`
- **Text Color**: `.text-primary`, `.text-secondary`, `.text-success`, `.text-info`, `.text-warning`, `.text-danger`, `.text-white`, `.text-muted`, `.text-black`
  
### **Grid System**
- `.container`, `.container-fluid`, `.container-{sm, md, lg, xl, xxl}`
- **Rows and Columns**: `.row`, `.col`, `.col-{1-12}`, `.col-sm`, `.col-md`, `.col-lg`, `.col-xl`, `.col-xxl`
- **Offsets**: `.offset-{1-11}`, `.offset-sm-{1-11}`
- **Gutters**: `.g-{0-5}`, `.gx-{0-5}`, `.gy-{0-5}`

### **Components**

#### **Alerts**
- `.alert`, `.alert-primary`, `.alert-secondary`, `.alert-success`, `.alert-danger`, `.alert-warning`, `.alert-info`, `.alert-light`, `.alert-dark`
- `.alert-dismissible`, `.alert-heading`, `.alert-link`

#### **Badges**
- `.badge`, `.badge-pill`, `.bg-primary`, `.bg-secondary`, `.bg-success`, `.bg-danger`, `.bg-warning`, `.bg-info`, `.bg-light`, `.bg-dark`

#### **Breadcrumbs**
- `.breadcrumb`, `.breadcrumb-item`, `.breadcrumb-item.active`

#### **Buttons**
- `.btn`, `.btn-primary`, `.btn-secondary`, `.btn-success`, `.btn-danger`, `.btn-warning`, `.btn-info`, `.btn-light`, `.btn-dark`, `.btn-link`
- **Button Sizes**: `.btn-sm`, `.btn-lg`
- **Button States**: `.disabled`, `.active`
- **Button Groups**: `.btn-group`, `.btn-toolbar`

#### **Card**
- `.card`, `.card-body`, `.card-header`, `.card-footer`, `.card-title`, `.card-subtitle`, `.card-img-top`, `.card-img-bottom`, `.card-text`, `.card-link`, `.card-group`

#### **Dropdowns**
- `.dropdown`, `.dropdown-menu`, `.dropdown-item`, `.dropdown-divider`, `.dropdown-header`, `.dropdown-toggle`, `.dropdown-menu-end`, `.dropup`, `.dropright`, `.dropleft`

#### **Forms**
- **Form Controls**: `.form-control`, `.form-select`, `.form-control-lg`, `.form-control-sm`
- **Input Group**: `.input-group`, `.input-group-text`, `.input-group-lg`, `.input-group-sm`
- **Validation States**: `.is-valid`, `.is-invalid`, `.valid-feedback`, `.invalid-feedback`

#### **List Group**
- `.list-group`, `.list-group-item`, `.list-group-item-action`, `.list-group-item-primary`, `.list-group-item-secondary`

#### **Modal**
- `.modal`, `.modal-dialog`, `.modal-content`, `.modal-header`, `.modal-body`, `.modal-footer`, `.modal-title`, `.modal-backdrop`
  
#### **Navs**
- `.nav`, `.nav-tabs`, `.nav-pills`, `.nav-fill`, `.nav-justified`, `.nav-link`, `.nav-item`, `.nav-vertical`

#### **Pagination**
- `.pagination`, `.page-item`, `.page-link`, `.pagination-lg`, `.pagination-sm`

#### **Progress**
- `.progress`, `.progress-bar`, `.progress-bar-striped`, `.progress-bar-animated`, `.bg-primary`, `.bg-success`, `.bg-info`

#### **Tooltips**
- `.tooltip`, `.bs-tooltip-start`, `.bs-tooltip-end`

Explore [Bootstrap Full Documentation](https://getbootstrap.com/docs/5.3/getting-started/introduction/) for the complete list of components and utilities.

---

# **Angular v18 Full Reference**

### **Structural Directives**
- `*ngIf`, `*ngFor`, `*ngSwitch`, `ngSwitchCase`, `ngSwitchDefault`

### **Attribute Directives**
- `[ngClass]`, `[ngStyle]`, `[ngModel]`, `[disabled]`, `[hidden]`, `[checked]`

### **Event Binding**
- `(click)`, `(submit)`, `(keyup)`, `(keydown)`, `(focus)`, `(blur)`, `(ngSubmit)`

### **Property Binding**
- `[src]`, `[href]`, `[disabled]`, `[value]`, `[class]`, `[style]`

### **Two-Way Binding**
- `[(ngModel)]`

### **Forms**
#### **Template-Driven Forms**
- `[ngModel]`, `[formGroup]`, `[formControl]`
  
#### **Reactive Forms**
- `FormControl`, `FormGroup`, `FormArray`, `Validators`, `FormBuilder`

### **Services**
- **HttpClient**: `.get()`, `.post()`, `.put()`, `.delete()`
- **ActivatedRoute**: `.params`, `.queryParams`, `.fragment`

### **Lifecycle Hooks**
- `ngOnInit()`, `ngOnDestroy()`, `ngAfterViewInit()`, `ngAfterContentInit()`, `ngDoCheck()`, `ngAfterContentChecked()`

### **Routing**
- `<router-outlet>`, `[routerLink]`, `[routerLinkActive]`, `RouterLink`, `RouterLinkActive`
- **Guards**: `CanActivate`, `CanDeactivate`, `Resolve`

For more, see [Angular Full Documentation](https://angular.io/guide/releases).

---

# **RxJS 7.8.1 Full Reference**

### **Creation Operators**
- `of()`, `from()`, `fromEvent()`, `interval()`, `timer()`, `range()`

### **Transformation Operators**
- `map()`, `switchMap()`, `concatMap()`, `mergeMap()`, `scan()`, `buffer()`, `bufferTime()`

### **Filtering Operators**
- `filter()`, `take()`, `takeUntil()`, `debounceTime()`, `distinctUntilChanged()`, `throttleTime()`

### **Combination Operators**
- `merge()`, `combineLatest()`, `concat()`, `withLatestFrom()`, `zip()`, `startWith()`

### **Error Handling Operators**
- `catchError()`, `retry()`, `retryWhen()`, `onErrorResumeNext()`

### **Utility Operators**
- `tap()`, `delay()`, `finalize()`, `repeat()`, `share()`, `multicast()`, `shareReplay()`

See [RxJS Full Documentation](https://rxjs.dev) for the full operator list and guides.

---

# **Angular Material Full Reference**

### **Typography**
- **Classes**: `.mat-h1

It seems my message got cut off. I'll now continue with the **complete Angular Material reference**.

---

# **Angular Material Full Reference**

### **Typography**
- **Classes**: `.mat-h1`, `.mat-h2`, `.mat-h3`, `.mat-h4`, `.mat-h5`, `.mat-h6`, `.mat-subtitle-1`, `.mat-subtitle-2`, `.mat-body-1`, `.mat-body-2`, `.mat-caption`, `.mat-overline`

### **Buttons**
- **Basic Button**: `<button mat-button>`, `<button mat-raised-button>`, `<button mat-icon-button>`, `<button mat-fab>`, `<button mat-mini-fab>`
- **Classes**: `.mat-button`, `.mat-raised-button`, `.mat-icon-button`, `.mat-fab`, `.mat-mini-fab`

### **Form Controls**
- **Text Fields**: `<mat-form-field>`, `<input matInput>`, `<textarea matInput>`, `<mat-error>`, `<mat-hint>`
- **Checkbox**: `<mat-checkbox>`, `.mat-checkbox-label`, `.mat-checkbox-inner-container`
- **Radio Buttons**: `<mat-radio-button>`, `<mat-radio-group>`
- **Select**: `<mat-select>`, `<mat-option>`, `.mat-select-placeholder`

### **Dialogs, Overlays, and Tooltips**
- **Dialog**: `<mat-dialog>`, `<mat-dialog-title>`, `<mat-dialog-content>`, `<mat-dialog-actions>`, `.mat-dialog-container`, `.mat-dialog-close`
- **Overlay**: `<mat-menu>`, `<mat-sidenav>`, `.mat-sidenav-container`
- **Tooltips**: `<mat-tooltip>`, `.mat-tooltip-trigger`

### **Navigation Components**
- **Toolbar**: `<mat-toolbar>`, `.mat-toolbar-row`, `.mat-toolbar-multiple-rows`, `.mat-toolbar-single-row`
- **Tabs**: `<mat-tab>`, `<mat-tab-group>`, `.mat-tab-label`, `.mat-tab-content`
- **Sidenav**: `<mat-sidenav>`, `<mat-sidenav-container>`, `.mat-sidenav-content`
  
### **Layout and Grid**
- **Grid List**: `<mat-grid-list>`, `<mat-grid-tile>`, `.mat-grid-tile-header`, `.mat-grid-tile-footer`
- **Flex Layout**: `.mat-flex`, `.mat-flex-align-start`, `.mat-flex-align-center`, `.mat-flex-align-end`, `.mat-flex-space-between`

### **Cards**
- `<mat-card>`, `<mat-card-header>`, `<mat-card-title>`, `<mat-card-subtitle>`, `<mat-card-content>`, `<mat-card-actions>`, `<mat-card-footer>`
- **Classes**: `.mat-card`, `.mat-card-header`, `.mat-card-title`, `.mat-card-subtitle`, `.mat-card-content`, `.mat-card-footer`

For a **full breakdown** of Angular Material components, see the [Angular Material Documentation](https://material.angular.io/components/categories).

---

This document contains a **complete, detailed cheatsheet** for **Bootstrap**, **Angular**, **RxJS**, and **Angular Material**, covering **all classes, tags, operators, and utilities**.