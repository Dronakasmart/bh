# Changelog

## 4.0.0
- Added global matcher support: `beforeEach` and `afterEach` (#121).
- Added `ctx.process` method (#135).
- Add `i-bem` class to element with `js` (#122).
- No-base modifier classes supported (#132).
- Wrap data-bem attribute by single quotes (#115).
- `processBemJson` now return standart BEMJSON (#96).
- Readme updates (#131, #124, #123, #120).
- Escaping optimizations (#137).

## 3.3.0
- Do not add `i-bem` class to element with `js`.

## 3.2.4
- Revert 3.2.1 and 3.2.2 patches.

## 3.2.3
- Speed improvement by better escaping (#111).
- `toHtml`: add mod === 0 to output (#110).

## 3.2.2
- Do not add `i-bem` class to mixed elements with `js`.

## 3.2.1
- Do not add `i-bem` class to element with `js` (#106).

## 3.2.0
- Escape content when option `escapeContent` enabled (#97).
- Some fixes.

## 3.1.4
- Ignore `mix` and `js` when `bem` is false (#98).

## 3.1.3
- TypeError when using elemMod matcher (#93).

## 3.1.2
- Falsy `return` should provide empty string result.

## 3.1.1
- `apply()`: do not fail on `undefined` (#83).
