<a name="0.0.3"></a>
# [0.0.3](https://www.npmjs.com/package/ngx-treeview) (2017-04-20)

### Upgrade project for Angular 4 from my old component: [ng2-dropdown-treeview](https://www.npmjs.com/package/ng2-dropdown-treeview)

# [0.0.5](https://www.npmjs.com/package/ngx-treeview) (2017-05-25)

### Enhancement: 
* Item always expands when matching search filter.

# [1.0.6](https://www.npmjs.com/package/ngx-treeview) (2017-07-10)

### Enhancement: 
* Build bundles.
* 100% code coverage.

# [1.0.7](https://www.npmjs.com/package/ngx-treeview) (2017-07-19)

### Enhancement:
* Template for header
```js
export interface TreeviewHeaderTemplateContext {
    config: TreeviewConfig;
    item: TreeviewItem;
    onCollapseExpand: () => void;
    onCheckedChange: (checked: boolean) => void;
    onFilterTextChange: (text: string) => void;
}
```
### Refactoring:
* Changes on interface of Treeview
```js
export interface TreeviewItemTemplateContext {
    item: TreeviewItem;
    onCollapseExpand: () => void;
    onCheckedChange: () => void;
}
```
* Changes on TreeviewConfig
```js
export class TreeviewConfig {
    hasAllCheckBox = true;
    hasFilter = false;
    hasCollapseExpand = false;
    maxHeight = 500;
}
```
### Demo:
* Example for ngx-dropdown-treeview-select component.

# [1.0.8](https://www.npmjs.com/package/ngx-treeview) (2017-07-20)
### Enhancement:
* Refactor CSS.
### Demo:
* Update examples.

# [1.0.9](https://www.npmjs.com/package/ngx-treeview) (2017-07-21)
### Enhancement:
* Expose DropdownDirective from DropdownTreeviewComponent.

# [1.1.0](https://www.npmjs.com/package/ngx-treeview) (2017-08-16)
### Enhancement:
* Support Bootstrap 4 beta.

# [1.2.0](https://www.npmjs.com/package/ngx-treeview) (2017-09-18)
### Enhancement:
* Support tri-state checkbox.

# [1.2.4](https://www.npmjs.com/package/ngx-treeview) (2017-10-19)
### Enhancement:
* Support configuration property to decouple parent and child.