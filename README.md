at-core-modal
=============

#### Modes of operation
at-core-modal has two modes of operation
* `desktop`
* `mobile`

#### Switching between modes
at-core-modal has `minWidth` property.

When browser window width is less then `minWidth` mode is `mobile`. Else, mode is `desktop`.

#### Operation of modal
Modal contents can have contents that has width smaller, equal or larger than browser window width. at-core-modal should fit content into available window width. Horizontal scrollbar should not appear.

Modal contents can have contents that has height which is smaller, equal or larger than browser window height.

If contents height is smaller or equal than browser window height, at-core-modal should be horizontally and vertically centered.

If contents height is larger than browser window height, at-core-modal
* should be horizontally centered,
* should have top and bottom margins
