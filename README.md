# css-utility-classes: Generic CSS utility classes

Classes designed for easily applying the spacing and alignments without needing to add new classes/modifiers for everything.

## Installation

`yarn add css-utility-classes`

## Classes

They are prefixed with `u-`. Classes that may require `!important` have an `i` suffix.

text-align: 
- `.u-text-right`
- `.u-text-left`
- `.u-text-center`

float: 
- `.u-float-right`
- `.u-float-left`
- `.u-float-none`

min-height: size is `0 - 200` incrementing up by `5px`
- `.mh-#{size}` for `margin`, `.mh-#{size}i` with `!important`

margin: size is `0 - 100` incrementing up by `5px`
- `.u-m-#{size}` for `margin`, `.u-m-#{size}i` with `!important`
- `.u-mt-#{size}` for `top-margin`
- `.u-mr-#{size}` for `right-margin`
- `.u-mb-#{size}` for `bottom-margin`
- `.u-ml-#{size}` for `left-margin`
- `.u-mx-#{size}` for `left-margin` and `right-margin`
- `.u-my-#{size}` for `top-margin` and `bottom-margin`

padding: size is `0 - 100` incrementing up by `5px`
- `.u-p-#{size}` for `padding`, `.u-p-#{size}i` with `!important`
- `.u-pt-#{size}` for `top-padding`
- `.u-pr-#{size}` for `right-padding`
- `.u-pb-#{size}` for `bottom-padding`
- `.u-pl-#{size}` for `left-padding`
- `.u-px-#{size}` for `left-padding` and `right-padding`
- `.u-py-#{size}` for `top-padding` and `bottom-padding`

## Development

Requires yarn or npm (use yarn don't be dumb).

Setup:
- `git clone git@github.com:postedin/css-utility-classes.git`
- `yarn setup`

Commands:
- `yarn build`
- `yarn run watch`

When committing git hooks will run `yarn build` and add the build to the current commit.

## Testing

Yolo.
