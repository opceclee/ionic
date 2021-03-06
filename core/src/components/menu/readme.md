# ion-menu

The Menu component is a navigation drawer that slides in from the side of the current view.
By default, it slides in from the left, but the side can be overridden.
The menu will be displayed differently based on the mode, however the display type can be changed to any of the available menu types.
The menu element should be a sibling to the root content element.
There can be any number of menus attached to the content.
These can be controlled from the templates, or programmatically using the MenuController.


<!-- Auto Generated Below -->


## Properties

| Property       | Attribute        | Description                                                                                                        | Type      |
| -------------- | ---------------- | ------------------------------------------------------------------------------------------------------------------ | --------- |
| `contentId`    | `content-id`     | The content's id the menu should use.                                                                              | `string`  |
| `disabled`     | `disabled`       | If true, the menu is disabled. Default `false`.                                                                    | `boolean` |
| `maxEdgeStart` | `max-edge-start` | The edge threshold for dragging the menu open. If a drag/swipe happens over this value, the menu is not triggered. | `number`  |
| `menuId`       | `menu-id`        | An id for the menu.                                                                                                | `string`  |
| `side`         | `side`           | Which side of the view the menu should be placed. Default `"start"`.                                               | `Side`    |
| `swipeGesture` | `swipe-gesture`  | If true, swiping the menu is enabled. Default `true`.                                                              | `boolean` |
| `type`         | `type`           | The display type of the menu. Available options: `"overlay"`, `"reveal"`, `"push"`.                                | `string`  |


## Events

| Event           | Description                                  |
| --------------- | -------------------------------------------- |
| `ionDidClose`   | Emitted when the menu is closed.             |
| `ionDidOpen`    | Emitted when the menu is open.               |
| `ionMenuChange` | Emitted when the menu state is changed.      |
| `ionWillClose`  | Emitted when the menu is about to be closed. |
| `ionWillOpen`   | Emitted when the menu is about to be opened. |


## Methods

### `close(animated?: boolean) => Promise<boolean>`



#### Parameters

| Name       | Type      | Description |
| ---------- | --------- | ----------- |
| `animated` | `boolean` |             |

#### Returns

Type: `Promise<boolean>`



### `isActive() => Promise<boolean>`



#### Returns

Type: `Promise<boolean>`



### `isOpen() => Promise<boolean>`



#### Returns

Type: `Promise<boolean>`



### `open(animated?: boolean) => Promise<boolean>`



#### Parameters

| Name       | Type      | Description |
| ---------- | --------- | ----------- |
| `animated` | `boolean` |             |

#### Returns

Type: `Promise<boolean>`



### `setOpen(shouldOpen: boolean, animated?: boolean) => Promise<boolean>`



#### Parameters

| Name         | Type      | Description |
| ------------ | --------- | ----------- |
| `shouldOpen` | `boolean` |             |
| `animated`   | `boolean` |             |

#### Returns

Type: `Promise<boolean>`



### `toggle(animated?: boolean) => Promise<boolean>`



#### Parameters

| Name       | Type      | Description |
| ---------- | --------- | ----------- |
| `animated` | `boolean` |             |

#### Returns

Type: `Promise<boolean>`




----------------------------------------------

*Built with [StencilJS](https://stenciljs.com/)*
