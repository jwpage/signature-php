# CHANGELOG

## 5.0.0

* `Request::payload()` and `Request::signature()` methods are now private. The `Request::sign()` method should be used instead.

## 4.0.0

* Fixes a security flaw due to not including `auth_*` fields in the signature payload.

## 3.0.3

* Fixed a bug where the `CheckTimestamp` guard would only protect against request timestamps in the past.

## 3.0.2

## 3.0.1

## 3.0.0

## 2.0.0

## 1.0.1

## 1.0.0