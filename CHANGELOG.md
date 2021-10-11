# Changelog for servant-to-elm

## Unreleased changes

## 0.4.3.0

- Add `HasElmEndpoints` instance for the new `Servant.NoContentVerb` type. Requires `servant` 0.17 or later.

## 0.4.2.0

- Use the `Url.Builder` module from `elm/url` to build URLs (https://github.com/folq/servant-to-elm/pull/6 by https://github.com/rl-king)
- Update `haskell-to-elm` bounds to latest version 0.3.2

## 0.4.1.0

- Update to `elm-syntax-0.3.0.0` and `haskell-to-elm-0.3.0.0`, adding support for parameterised types

## 0.4.0.0

- Make endpoints that return NoContent (HTTP status code 204) return `()` on the Elm side, and remove instances for the `NoContent` type

## 0.3.1.0

- Update to `elm-syntax-0.2.0.0`, adding simplification of the generated definitions.

## 0.3.0.0

- Add support for multipart forms

## 0.2.0.0

- Update code with changes from `haskell-to-elm-0.2.0.0`

## 0.1.0.0

- Initial release
