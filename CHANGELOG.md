# CHANGELOG

## [2.0.0](https://github.com/garuda-tunnel/openid_connect-internal/compare/v1.0.0...v2.0.0) (2026-10-31)


### Bug Fixes

* edge case verification failure ([#34](https://github.com/garuda-tunnel/openid_connect-internal/issues/34)) ([e8dfd00](https://github.com/garuda-tunnel/openid_connect-internal/commit/e8dfd0033bb3420c1af43653406ccd870900032e))
* OTP 29 / Elixir 1.20 compatibility ([#2](https://github.com/garuda-tunnel/openid_connect-internal/issues/2)) ([a5031ef](https://github.com/garuda-tunnel/openid_connect-internal/commit/a5031ef0acbe790d24af6a337054e6a90166bc0d))

## v0.2.2
* Allow missing `claims_supported` in discovery document
* Allow overriding document params

## v0.2.1
* Relaxed jason version requirement

## v0.2.0
* BREAKING CHANGE - Multiple response types supported. See: PR #17 for details

## v0.1.2
* Optional params for `authorization_uri`

## v0.1.1

* Remove Poison (legacy dep)
* Force JOSE to use Jason in test suite

## v0.1.0

* Initial public release
