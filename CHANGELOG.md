# Changelog

### 0.2.0

* Monad.Fail no longer exists in `base-4.13.0.0` and beyond; the function now
  lives in the class `MonadFail`. We need a major version bump, because this
  change affects the type signatures of functions we export to our users.

### 0.1.3

* Improve performance of parsing multipart body. Thanks to Ali Abrar.

### 0.1.2

* Expose `Network.Multipart.Header`
