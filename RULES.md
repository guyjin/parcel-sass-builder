These rules are taken from the Stylelint [documentation](https://stylelint.io/user-guide/rules). These are the rules that are on by default in the Stylelint [config](https://github.com/stylelint/stylelint-config-standard).

---

# Rules to avoid errors

You can avoid errors with these _no_ rules.

## Descending

Disallow descending things with these `no-descending` rules.

`no-descending-specificity`

Disallow selectors of lower specificity from coming after overriding selectors of higher specific

---

## Duplicate

Disallow duplicates with these `no-duplicate` rules.

`declaration-block-no-duplicate-custom-properties`
Disallow duplicate custom properties within declaration blocks.

`declaration-block-no-duplicate-properties`
Disallow duplicate properties within declaration blocks.

`font-family-no-duplicate-names`
Disallow duplicate names within font families.

`keyframe-block-no-duplicate-selectors`
Disallow duplicate selectors within keyframe blocks.

`no-duplicate-at-import-rules`
Disallow duplicate @import rules.

`no-duplicate-selectors`
Disallow duplicate selectors

## Empty

Disallow empty things with these `no-empty` rules.

`block-no-empty`
Disallow empty blocks.

`comment-no-empty`
Disallow empty comments.

`no-empty-source`
Disallow empty sources.

## Invalid

Disallow invalid syntax with these (sometimes implicit) `no-invalid` rules.

`color-no-invalid-hex`
Disallow invalid hex colors.

`function-calc-no-unspaced-operator`
Disallow invalid un-spaced operator within calc functions.

`keyframe-declaration-no-important`
Disallow invalid !important within keyframe declarations.

`media-query-no-invalid`
Disallow invalid media queries.

`named-grid-areas-no-invalid`
Disallow invalid named grid areas.

`no-invalid-double-slash-comments`
Disallow invalid double-slash comments.

`no-invalid-position-at-import-rule`
Disallow invalid position @import rules.

`string-no-newline`
Disallow invalid newlines within strings.

## Missing

Disallow missing things with these `no-missing` rules.

`custom-property-no-missing-var-function`
Disallow missing var function for custom properties.

`font-family-no-missing-generic-family-keyword`
Disallow a missing generic family keyword within font families.

## Non-Standard

Disallow non-standard things with these `no-nonstandard` rules.

`function-linear-gradient-no-nonstandard-direction`
Disallow non-standard direction values for linear gradient functions.

## Overrides

Disallow overrides with these `no-overrides` rules.

`declaration-block-no-shorthand-property-overrides`
Disallow shorthand properties that override related longhand properties.

## Unmatchable

Disallow unmatchable things with these `no-unmatchable` rules.

`selector-anb-no-unmatchable`
Disallow unmatchable An+B selectors.

## Unknown

Disallow unknown things with these `no-unknown` rules.

`annotation-no-unknown`
Disallow unknown annotations.

`at-rule-no-unknown`
Disallow unknown at-rules.

`function-no-unknown`
Disallow unknown functions.

`media-feature-name-no-unknown`
Disallow unknown media feature names.

`property-no-unknown`
Disallow unknown properties.

`selector-pseudo-class-no-unknown`
Disallow unknown pseudo-class selectors.

`selector-pseudo-element-no-unknown`
Disallow unknown pseudo-element selectors.

`selector-type-no-unknown`
Disallow unknown type selectors.

`unit-no-unknown`
Disallow unknown units.

# Enforce Conventions

You can enforce conventions with these `no` and `list` rules. They are powerful rules for making your code consistent. You'll need to configure most of them to suit your needs.

## Allowed, disallowed & required

Allow, disallow or require things with these `allowed-list`, `disallowed-list`, `required-list` and `no` rules.

### At-rule

`at-rule-no-vendor-prefix`
Disallow vendor prefixes for at-rules.

### Length

`length-zero-no-unit`
Disallow units for zero lengths.

### Media feature

`media-feature-name-no-vendor-prefix`
Disallow vendor prefixes for media feature names.

### Property

`property-no-vendor-prefix`
Disallow vendor prefixes for properties.

### Selector

`selector-no-vendor-prefix`
Disallow vendor prefixes for selectors.

### Value

`value-no-vendor-prefix`
Disallow vendor prefixes for values.

## Case

Specify lowercase or uppercase for words with these `case` rules.

`function-name-case`
Specify lowercase or uppercase for function names.

`selector-type-case`
Specify lowercase or uppercase for type selectors.

`value-keyword-case`
Specify lowercase or uppercase for keywords values.

### Empty lines

Enforce or disallow empty lines before constructs with these `empty-line-before` rules.

`at-rule-empty-line-before`
Require or disallow an empty line before at-rules.

`comment-empty-line-before`
Require or disallow an empty line before comments.

`custom-property-empty-line-before`
Require or disallow an empty line before custom properties.

`declaration-empty-line-before`
Require or disallow an empty line before declarations.

`rule-empty-line-before`
Require or disallow an empty line before rules.

### Max & min

Apply limits with these max and min rules.

`declaration-block-single-line-max-declarations`
Limit the number of declarations within a single-line declaration block.

`number-max-precision`
Limit the number of decimal places allowed in numbers.

### Notation

Enforce one representation of things that have multiple with these `notation` (sometimes implicit) rules.

`alpha-value-notation`
Specify percentage or number notation for alpha-values.

`color-function-notation`
Specify modern or legacy notation for color-functions.

`color-hex-length`
Specify short or long notation for hex colors.

`font-weight-notation`
Specify numeric or named notation for font weights.

`hue-degree-notation`
Specify number or angle notation for degree hues.

`import-notation`
Specify string or URL notation for @import rules.

`keyframe-selector-notation`
Specify keyword or percentage notation for keyframe selectors.

`lightness-notation`
Specify number or percentage notation for lightness.

`media-feature-range-notation`
Specify context or prefix notation for media feature ranges.

`selector-not-notation`
Specify simple or complex notation for :not() pseudo-class selectors.

`selector-pseudo-element-colon-notation`
Specify single or double colon notation for applicable pseudo-element selectors.

### Pattern

Enforce naming conventions with these `pattern` rules.

`custom-media-pattern`
Specify a pattern for custom media query names.

`custom-property-pattern`
Specify a pattern for custom properties.

`keyframes-name-pattern`
Specify a pattern for keyframe names.

`selector-class-pattern`
Specify a pattern for class selectors.

`selector-id-pattern`
Specify a pattern for ID selectors.

### Quotes

Require or disallow quotes with these quotes rules.

`font-family-name-quotes`
Require or disallow quotes for font family names.

`function-url-quotes`
Require or disallow quotes for urls.

`selector-attribute-quotes`
Require or disallow quotes for attribute values.

### Redundant

Disallow redundancy with these no-redundant rules.

`declaration-block-no-redundant-longhand-properties`
Disallow redundant longhand properties within declaration-block.

`shorthand-property-no-redundant-values`
Disallow redundant values within shorthand properties.

### Whitespace inside

Require or disallow whitespace on the inside with this whitespace-inside rule.

`comment-whitespace-inside`
Require or disallow whitespace on the inside of comment markers.
